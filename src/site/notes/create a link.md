---
{"dg-publish":true,"permalink":"/create-a-link/"}
---

very cool ey
![Pasted image 20260204153937.png](/img/user/Pasted%20image%2020260204153937.png)


## Idea
Publish some #project  and #issue notes for people to read.

URL Would be `notes.gozynta.com/<USER>`

Setup some kind of SSO frontend, in order to keep the notes private.

[GitHub - oleeskild/obsidian-digital-garden](https://github.com/oleeskild/obsidian-digital-garden)


[GitHub - PidgeyL/digitalgarden-selfhosted: Self-Host Obsidian Digital Garden](https://github.com/PidgeyL/digitalgarden-selfhosted)


```mermaid
flowchart LR
notes.gozynta.com/joppe --> login[login with google-username] --> Keycloak --> notes-pages
```

1. [ ] Setup domain name
2. [ ] Figure out some kind of (hopefully) off the shelf authentication solution. Keycloak?
3. [ ] Note page needs an auth-token
