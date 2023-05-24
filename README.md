 
 <h1 align="center">Hi 👋, I'm Khoa Nguyen</h1>
<h3 align="center">Coder</h3>

<p align="center">
  <a href="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=nguyen2109&theme=vue">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=nguyen2109&theme=vue" />
  </a>
 
  <a href="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=nguyen2109&theme=vue&utcOffset=7">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=nguyen2109&theme=vue&utcOffset=7" />
  </a>
 
  <a href="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=nguyen2109&theme=vue">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=nguyen2109&theme=vue" />
  </a>
 
 <a href="https://github-readme-streak-stats.herokuapp.com/?user=nguyen2109&hide_border=true&card_width=150&theme=vue">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=nguyen2109&hide_border=true&card_width=150&theme=vue" />
  </a> 
 
 <a href="https://github-readme-stats.vercel.app/api/wakatime?username=nguyen2109&card_width=150&hide_border=true&theme=vue">
    <img src="https://github-readme-stats.vercel.app/api/wakatime?username=nguyen2109&hide_border=true&theme=vue&card_width=150" />
  </a>
 
  <a href=""> 
   <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=nguyen2109&card_width=699&hide_border=true&theme=vue"/> 
 </a>
 
 
 
 
</p>

<details>
 
# My .prettierrc config :

First, install Prettier locally:

```sh
npm install --save-dev --save-exact prettier
```

Then, create an empty config file to let editors and other tools know you are using Prettier:

```sh
echo {}> .prettierrc.json
```

Now, format all files with Prettier :

```sh
npx prettier --write .
```

```sh
npx prettier --check .
```

## .prettierrc config :

```sh
{
  "tabWidth": 2,
  "printWidth": 80,
  "semi": true,
  "singleQuote": true,
  "trailingComma": "all"
}
```

# .gitignore config :

```sh
node_modules/
```

# .eslintrc.json config :

```sh
{
  "extends": ["airbnb", "prettier", "plugin:node/recommended"],
  "plugins": ["prettier"],
  "rules": {
    "prettier/prettier": "error",
    "spaced-comment": "off",
    "no-console": "warn",
    "consistent-return": "off",
    "func-names": "off",
    "object-shorthand": "off",
    "no-process-exit": "off",
    "no-param-reassign": "off",
    "no-return-await": "off",
    "no-underscore-dangle": "off",
    "class-methods-use-this": "off",
    "prefer-destructuring": ["error", { "object": true, "array": false }],
    "no-unused-vars": ["error", { "argsIgnorePattern": "req|res|next|val" }]
  }
}
```
</details>
