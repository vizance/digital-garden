<%*
    const title = await tp.system.prompt("Title")
    await tp.file.rename(`${title}`)
%>---
title: "<%* tR += title %>"
date: "<% tp.file.creation_date("YYYY-MM-DD") %>"
aliases: []
tags: Writing
---


- 1
- 2
- 3