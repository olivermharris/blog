---
title: <% tp.file.title %>
---

<< [[journal/daily/<% moment(tp.file.title,'YYYY-MM-DD').add(-1,'days').format("YYYY-MM-DD") %>|⏪ Yesterday(<% moment(tp.file.title,'YYYY-MM-DD').add(-1,'days').format("YYYY-MM-DD") %>)]] | [[journal/weekly/<% moment(tp.file.title,'YYYY-MM-DD').format("YYYY") %>-W<% moment(tp.file.title, "YYYY-MM-DD").isoWeek() %>|Week: <% moment(tp.file.title, "YYYY-MM-DD").isoWeek() %>]] | [[journal/daily/<% moment(tp.file.title,'YYYY-MM-DD').add(1,'days').format("YYYY-MM-DD") %>|Tomorrow(<% moment(tp.file.title,'YYYY-MM-DD').add(1,'days').format("YYYY-MM-DD") %>) ⏩]] >>

# <% tp.file.title %>