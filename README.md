<!--
    This is the README.md file.
    It's used to explain your bot to other users
    Include information as:
      - why should someone use your bot
      - does your bot has his own website?
      - does your bot have documentation?
    To write the REAMDE.md yoou can use Markodwn
    syntax or html syntax.
-->
<h1 align="center">Name of your bot</h1>
<!--
    Modify using this format:
    <img alt="Name of the image" src="path to the image">
-->
<p align="center">
  <a href="invite link of your bot">
    <img alt="Logo example" src="img/logo-example.png">
  </a>
</p>


### You can invite the bot to your sevrer using [this](bot invite link) link.

##### For contributing to the bot's code, read the [CONTRIBUTING.md](CONTRIBUTING.md) file.

---

### Table of c(https://git-scm.com/downloads)ontents
- [Idea](#idea)
- [Commands](#commands)
- [Compiling from source](#compiling-from-source)
- [License](#license)
--- 

### Idea
**DESCRIPTION OF YOUR BOT**: 
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque sit amet consequat magna. Nam malesuada vitae tortor id aliquam. Praesent congue lectus quis neque scelerisque euismod. Pellentesque malesuada diam ut purus facilisis, et ultricies tellus vulputate. Sed a consequat ipsum. Vivamus dui neque, venenatis non dui vitae, mattis pulvinar nisl. Praesent vitae viverra mi.

---

### Commands
All the commands start with the prefix `/`

| Name              | Description                               |
|-------------------|-------------------------------------------|
| hello             | Say hello to the bot!                     |
| ...               | ...                                       |
| ...               | ...                                       |

---

### Compiling from source
If you want to compile the bot's code to then run it in a local server, you will need:

| Name     | Version | Use | Links|
|----------|---------|-----|------|
| Git      | v0.9+   | Clonning the repository to your computer | [install](https://git-scm.com/downloads) [docs](https://git-scm.com/doc)  |
| Go tool  | v0.5.0+ | Building the actual bot as an executable | [install](https://golang.org) [docs](https://golang.org/cmd/go/)          |

Then, run open a terminal / cmd and run:
###### Clone the repository
```shell
git clone https://github.com/<your github username>/<your bot's repository name>.git
```

<!--
    NOTE: You can use this template for your own bot,
    so change the strings between "<" and ">" to your
    github username and the name of your repository
-->

###### Move inside the repository
```shell
cd <your bot's repository name>/bot
```
###### Use the Golang tool to build the code
```shell
go build -o bot
```
###### Execute the code
```shell
./bot
```

---

### License

<!--
  By default this project is under the mit license.
    
    https://opensource.org/licenses/MIT

  You can change it in the "LICENSE" file of your
  repository.
-->

This project is under the [MIT License](LICENSE)
