## Hi there 👋 
### Welcome to my GitHub profile!

```php
<?php
namespace gitHub\profile

Class User
{
  public const string FIRSTNAME = 'Nicolas';
  public const string LASTNAME = 'Garcia';
  public int $age;
  
  public function __construct(){
    $born = new DateTimeImmutable('1979-01-12');
    $today = new Datetime();
    $interval = $born->diff($today)->format('%Y ans');
    $this->age = $interval;
  }
}
```

[![Les Stats GitHub de Nicolas](https://github-readme-stats.vercel.app/api?username=NicolasGarciaCdl)](https://github.com/nicolasgarciacdl/github-readme-stats)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=nicolasgarciacdl)](https://github.com/nicolasgarciacdl/github-readme-stats)


<!--
**NicolasGarciaCdl/NicolasGarciaCdl** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
