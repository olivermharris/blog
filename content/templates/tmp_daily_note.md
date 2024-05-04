---
title: <% tp.file.title %>
---

<< [[Journal/Daily/<% moment(tp.file.title,'YYYY-MM-DD').add(-1,'days').format("YYYY-MM-DD") %>|⏪ Yesterday(<% moment(tp.file.title,'YYYY-MM-DD').add(-1,'days').format("YYYY-MM-DD") %>)]] | [[Journal/Weekly/<% moment(tp.file.title,'YYYY-MM-DD').format("YYYY") %>-W<% moment(tp.file.title, "YYYY-MM-DD").isoWeek() %>|Week: <% moment(tp.file.title, "YYYY-MM-DD").isoWeek() %>]] | [[Journal/Daily/<% moment(tp.file.title,'YYYY-MM-DD').add(1,'days').format("YYYY-MM-DD") %>|Tomorrow(<% moment(tp.file.title,'YYYY-MM-DD').add(1,'days').format("YYYY-MM-DD") %>) ⏩]] >>

