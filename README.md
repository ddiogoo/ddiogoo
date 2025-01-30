### Hi there 👋

#### Let's keep in touch 👇

[![LinkedIn][1]][2] [![StackOverflow][3]][4]

[1]:  https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white
[2]:  https://www.linkedin.com/in/ddiogoo "My LinkedIn Profile"
[3]:  https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white
[4]:  https://stackoverflow.com/users/21128126/diogo-martins-de-assis "My StackOverflow Profile"

```proto
message AboutMe {
  option (api_version) = 22;
  option (created_at) = {
    chinese_year: "🐴",
    year: 2002,
    month: AUGUST,
    day: 28
  };
  option (kind) = HUMAN;
  option (metadata) = {
    name: "Diogo Martins de Assis",
    from: "🇧🇷",
    live_in: "🇧🇷",
    languages: [ CS, GOLANG, JAVA, JS, PYTHON ]
  };
  option (status).work = CODING;
  option (spec).purpose = "Solve Software Engineering Problems";
  option (favorite) = {
    number: 4,
    programing_language: PROGRAMING_LANGUAGE_UNSPECIFIED,
    emoji_sequence: "🙈🙉🙊"
  };
}
```
