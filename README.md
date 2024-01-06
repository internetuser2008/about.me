![Bimal Patel Banner Image](./internetuser2008.gif)
<!-- <h2 align='center'>
**internetuser2008/Bimal.Patel** is a ✨ _special_ ✨ repository because its `Data Engineer/DevOps` </h2> (this file) appears on your GitHub profile.
-->
### Hi there 👋

[![Visitor](https://visitor-badge.laobi.icu/badge?page_id=internetuser2008/internetusre2008)](https://github.com/internetuser2008) [![GitHub followers](https://img.shields.io/github/followers/internetuser2008.svg?style=social&label=Follow)](https://github.com/internetuser2008?tab=followers)



- 🔭 I’m Open Source Database Engineer
- 🌱 I’m currently learning Everything!!!
- 👯 I’m looking to collaborate Renformenet Learning
- 🤔 I’m looking for help with ...
- 💬 Ask me about Postgres
- 📫 How to reach me: 
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|




## PG Cluster
```mermaid
graph LR
A[Connection pooler-dc1] -- Writes --> B((PG1 dc1))
A -- Reads --> C(PG2 dc2)
B -- Replication --> D{PG3 dc1}
A -- Reads --> D
B -- Replication --> C
```
