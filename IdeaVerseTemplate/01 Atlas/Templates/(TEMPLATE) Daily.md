---
date: <%tp.date.now("YYYY-MM-DD")%>T<%tp.date.now("hh:mm A")%>
tags:
  - Daily
cssclasses:
  - daily
  <% "- " + tp.date.now("dddd", 0, tp.file.title, "YYYYMMDD").toLowerCase() %>
---
# DAILY NOTE
## <% tp.date.now("dddd, MMMM Do, YYYY", 0, tp.file.title, "YYYYMMDD") %>


***
### Journal
#### <%tp.date.now("hh:mm A")%>
...
> [!OneThing] 
> ...

### Tasks
- [ ] 10k Steps 
- [ ] Deep Work 
- [ ] 45 min workout
- [ ] Shower 



