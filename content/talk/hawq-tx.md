+++
date = "2017-03-23T15:30:00"
title = "Apache HAWQ的事务处理"
abstract = ""
abstract_short = "HAWQ Transaction Introduction"
event = "Apache HAWQ Meetup @ Beijing"
event_url = "https://cwiki.apache.org/confluence/display/HAWQ/Community"
location = "Beijing, China"

selected = false
math = true

url_pdf = ""
url_slides = "https://cwiki.apache.org/confluence/download/attachments/61320901/HAWQ%20Transaction%20Introduction.pdf?version=1&modificationDate=1490600276000&api=v2"
url_video = "https://v.qq.com/x/page/v0391aslvhs.html"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

+++

这个是在3月23日举办的HAWQ技术研讨会中本人做的技术演讲，本次演讲首先为大家介绍了PostgreSQL的事务处理中的多版本并发控制，然后结合了HAWQ的应用场景，介绍在HAWQ怎么实现事务并发控制，以及并行插入优化等问题，并解释了一些HAWQ使用的注意事项和将来可以考虑实现的一些方案。