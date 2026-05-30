<div align="center">

# ⚔️ Seja bem-vindo ao meu perfil!

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D9FF&center=true&vCenter=true&width=500&lines=Game+Developer+%F0%9F%8E%AE;Unreal+Engine+%7C+Unity;C%2B%2B+%7C+C%23;Building+worlds%2C+one+frame+at+a+time" alt="Typing SVG" />

</div>

---

## 🧰 Tech Stack

<div align="center">

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-313131?style=for-the-badge&logo=unrealengine&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)

</div>

---

## 🎮 Sobre mim

```cpp
class Developer {
public:
    std::string name     = "Seu Nome";
    std::string role     = "Game Developer";
    std::string location = "Brasil 🇧🇷";

    std::vector<std::string> engines = {
        "Unreal Engine 5",
        "Unity"
    };

    std::vector<std::string> languages = {
        "C++", "C#", "Blueprints (UE5)"
    };

    std::string currentFocus() {
        return "Criando experiências imersivas 🚀";
    }
};
```

---

## ⚙️ O que eu faço

| Motor | Linguagem | Especialidade |
|-------|-----------|--------------|
| 🎮 Unreal Engine | C++ / Blueprints | AAA Games, Renderização realista |
| 🕹️ Unity | C# | Mobile, Indie, Protótipos rápidos |

---

## 🚀 Projetos em destaque

### 🔥 [Nome do Projeto 1](https://github.com/TucanoiDEV/projeto1)
> Breve descrição do que o projeto faz. Desenvolvido em **Unreal Engine 5** com C++.

![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine%205-313131?style=flat-square&logo=unrealengine&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

---

### 🎯 [Nome do Projeto 2](https://github.com/TucanoiDEV/projeto2)
> Breve descrição do que o projeto faz. Desenvolvido em **Unity** com C#.

![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)

---

## 📊 Estatísticas do GitHub

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=TucanoiDEV&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=FFFFFF)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=TucanoiDEV&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=FFFFFF)

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

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/TucanoiDEV)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=firefox&logoColor=white)](https://seusite.com)
[![itch.io](https://img.shields.io/badge/itch.io-FA5C5C?style=for-the-badge&logo=itchdotio&logoColor=white)](https://TucanoiDEV.itch.io)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:seuemail@email.com)

</div>

---

<div align="center">

*"Os melhores jogos são aqueles que fazem o jogador esquecer que está jogando."*

![Visitor Count](https://komarev.com/ghpvc/?username=TucanoiDEV&color=00D9FF&style=flat-square)

</div>
