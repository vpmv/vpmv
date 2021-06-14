# Code, rinse, repeat

```go
import (
  "time"
  "math/rand"
)

func main() {
  for {
    t := time.Now().Hour()
    switch {
    case t > 8 && t < 18:
      work()
    case t >= 18 && t <= 23:
      freetime()
    }
    time.Sleep(3600 * time.Second)
  }
}

func work() {
  tasks := []string{"code", "read", "discuss"}
  log.Println(tasks[rand.Intn(len(tasks))])
}

func freetime() {
  tasks := []string{"sit in garden", "listen to music", "horse around"} # i don't eat
  log.Println(tasks[rand.Intn(len(tasks))])
}
```
# But seriously

I spend most of the time here browsing sources for my full-time job.<br>
I'm mostly proficient in GoLang & PHP. Front-end isn't my strong suit, but I manage.

My online actions are not a representation of my being, skills or capabilities. I know the code above may well just be a cronjob, don't worry &#128521;.

## Head hunters

I have a [JSON resume](https://registry.jsonresume.org/vpmv)

<!--
**vpmv/vpmv** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
