Tags:
Links: [[2021-W<% tp.date.now("WW", 7) %>]]
___
# <%tp.date.now("YYYY-MM-DD")%>
<< [[<%tp.date.now("YYYY-MM-DD", -1)%>]] - [[<%tp.date.now("YYYY-MM-DD", 1)%>]] >>
## Reminders
- Check Google Calendar for any events
- [[My Daily Laws]]
- ![[<%tp.date.now("YYYY-MM-DD", -1)%>#Improvement for Tomorrow]]
### Today's Tasks
> Refer to [[To Do's (Tq)]]

**ONE 1-2+ Hours Task:**
- [ ] <%tp.file.cursor(1)%>
<%* if (tp.date.now("ddd") == "Sun") { %>
- [ ] Make Weekly Note
<%* } %>
<%* if (tp.date.now("D") == 1) { %>
- [ ] Make Monthly Note
<%* } %>
<%* if (tp.date.now("M-D") == "1-1") { %>
- [ ] Make Yearly Note
<%* } %>
**THREE 30-60 Minute Tasks**:
- [ ] <%tp.file.cursor(2)%>

**FIVE 10-30 Minute Tasks**:
- [ ] <%tp.file.cursor(3)%>
## Journals
### Gratitude
#### Life (3)
<%tp.file.cursor(4)%>
#### Personal (3)
<%tp.file.cursor(5)%>
<%* if (tp.date.now("ddd") != "Sun" && tp.date.now("ddd") != "Sat") { %>
### Stocks
**How is the portoflio doing? Did you do any management?**
- 

**What is the daily reddit thread talking about today?**
- 

**What did I learn or should keep in mind?**
- 
<%* } %>
### Schedule
%% You must have a dailies file for this to work, uncomment once you have one :) %%
%% <%tp.file.include("[[Dailies]]")%> %%
## Reflection
### Lingering Feelings, Observations, Thoughts

### Productivity
#### Book Implementation
**What was today's event? What do I feel about my behavior? Is there something I can work on?**
- 
**Was I personal with my conversations, or was I generic? How did other people respond?**
- 
#### Previous Improvement Effectiveness 
- 
#### Good
- 
#### Bad
**What's one point of pain from today? How did it feel? How can I learn from it?**
- 
#### Improvement for Tomorrow
- 
___
## Today's Notes
```query
line:("Created:: <%tp.date.now("YYYY-MM-DD")%>")
```
___
