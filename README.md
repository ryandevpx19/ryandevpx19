<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/profile-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/profile-light.svg">
  <img alt="Ryan Henrique terminal profile" src="./assets/profile-dark.svg" width="100%">
</picture>

<p align="center"><code>ryan@github:~$ ./production.sh</code></p>

<p align="center">
  <img src="https://i.pinimg.com/originals/c1/97/e1/c197e1fc5e0178579c3ef6e98fb33ab1.gif" width="280" alt="production cat">
</p>

<p align="center"><sub>production is fine. please do not check the logs.</sub></p>

---

<details>
<summary><b>🚨 production incident protocol</b></summary>

```bash
sudo systemctl restart everything
docker compose down && docker compose up -d
git reset --hard HEAD~1
clear
echo "ninguém viu nada"
```

**Root cause:** unknown  
**Solution:** restart  
**Lessons learned:** none

</details>

<details>
<summary><b>🧠 source code</b></summary>

```js
while (alive) {
  code();

  if (production.isDown()) {
    console.log("estranho, aqui funciona");
  }
}
```

</details>

<p align="center"><b>IT WORKS ON MY MACHINE™</b><br><sub>therefore the machine is now the server.</sub></p>
