---
title: FAQ
description: Frequently Asked Questions about the Trike tool or threat modeling methodology.
---

# Questions
{% for question in site.faq %}
<div class="faqquestion"><a href="#question_{{ forloop.index }}">{{ forloop.index }}. {{ question.question }}</a></div>
{% endfor %}

# Answers
{% for question in site.faq %}

<div id="question_{{ forloop.index }}" class="faqquestion">{{ forloop.index }}. {{ question.question }}</div>
<div class="faqanswer">
	{{ question.content }}
</div>
{% endfor %}
