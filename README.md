
## 📊 Estatísticas do GitHub

<div align="center">

![GitHub Stats](https://github-readme-stats-git-master-denvercoder1.vercel.app/api?username=TucanoiDEV&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=FFFFFF)

![Top Langs](https://github-readme-stats-git-master-denvercoder1.vercel.app/api/top-langs/?username=TucanoiDEV&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=FFFFFF)

</div>

---

## 🧪 Exemplos de código

### C++ — Unreal Engine: Movimento de personagem
```cpp
void AMyCharacter::SetupPlayerInputComponent(UInputComponent* PlayerInputComponent)
{
    Super::SetupPlayerInputComponent(PlayerInputComponent);

    PlayerInputComponent->BindAxis("MoveForward", this, &AMyCharacter::MoveForward);
    PlayerInputComponent->BindAxis("MoveRight",   this, &AMyCharacter::MoveRight);
    PlayerInputComponent->BindAction("Jump", IE_Pressed, this, &ACharacter::Jump);
}

void AMyCharacter::MoveForward(float Value)
{
    if (Controller && Value != 0.f)
    {
        const FRotator Rotation = Controller->GetControlRotation();
        const FVector  Direction = FRotationMatrix(Rotation).GetUnitAxis(EAxis::X);
        AddMovementInput(Direction, Value);
    }
}
```

### C# — Unity: Sistema de saúde simples
```csharp
public class HealthSystem : MonoBehaviour
{
    [SerializeField] private float maxHealth = 100f;
    private float currentHealth;

    void Start() => currentHealth = maxHealth;

    public void TakeDamage(float damage)
    {
        currentHealth = Mathf.Max(currentHealth - damage, 0f);
        if (currentHealth <= 0f) Die();
    }

    public void Heal(float amount) =>
        currentHealth = Mathf.Min(currentHealth + amount, maxHealth);

    private void Die() => Debug.Log($"{gameObject.name} foi derrotado!");
}
```

---

## 🌐 Conecte-se comigo

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rodrigo-henrique-a5184830a/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=firefox&logoColor=white)](https://portfolio-eight-tau-l09p2flzet.vercel.app/)
[![itch.io](https://img.shields.io/badge/itch.io-FA5C5C?style=for-the-badge&logo=itchdotio&logoColor=white)](https://tucanoidev.itch.io)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tucanogithub@email.com)

</div>

---

<div align="center">

## Github status:

<br>
<a href="https://github.com/heitorviana-dev/convoychat">
 <img src= "https://github-readme-streak-stats-eight.vercel.app/?user=TucanoiDEV&theme=dark&border_radius=4.7&show_icons=true&count_private=true" width="51%" alt="stats graph" />
</a>

![Visitor Count](https://komarev.com/ghpvc/?username=TucanoiDEV&color=00D9FF&style=flat-square)

</div>
