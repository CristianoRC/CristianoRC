<p align="center">
  <img width="150px" src="https://www.cristianoprogramador.com/img/Cristiano(logo)%20Sem%20Texto.png"/>
</p>
<p align="center">
  <a href="https://medium.com/cristiano-cunha">Blog</a> •
  <a href="https://www.linkedin.com/in/cristianorc/">LinkedIn</a> •
  <a href="https://cristianoprogramador.com">Site</a> •
  <a href="https://www.youtube.com/channel/UCeDFP_iLSFUACJ1E0yLGgkw">Youtube</a> •
  <a href="mailto:contato@cristianoprogramador.com">E-mail</a> 
</p>

<p align="center">
  Olá, Meu nome é Cristiano, desenvolvedor .NET. Apaixonado por desenvolvimento de software, educação e o mundo open source.
</p>

```cs

    public static void Main()
    {
        var cristianoCunha = new SoftwareDeveloper()
        {
            Name = "Cristiano Raffi Cunha",
            Title = "Desenvolvedor .NET | Instrutor",
            Company = "Trybe",
            Location = "Pelotas - Rio Grande do Sul",
            Email = new Email("Contato@CristianoProgramador.com")
        };


        var skills = new Skills()
        {
            Languages = new[] { "C#", "JavaScript", "Typescript" },
            Frameworks = new[] { ".NET", "Angular", "Vue" },
            Technologies = new[] { "Docker", "Azure", "Linux" }
        };

        cristianoCunha.SetSkill(skills);
    }
```
