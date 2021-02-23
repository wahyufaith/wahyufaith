# Hi 👋, I'm wahyufaith
#### passionate about artificial intelligence and web development
<!--
**wahyufaith/wahyufaith** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
![Wahyu GitHub stats](https://github-readme-stats.vercel.app/api?username=wahyufaith&theme=dark&show_icons=true)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=wahyufaith&theme=dark&show_icons=true&layout=compact)](https://github.com/wahyufaith/github-readme-stats)

const f = s => {
  if (typeof s === `string`) {
    return `Its a String`
  }

  if (Array.isArray(s)) {
    return `Its an Array`
  }

  throw new Error(`Supplied value was invalid`)
}

const value = null
expect(() => f(value)).Throw(`Supplied value was invalid`)
