{% from "common/topics.njk" import panopto, slugify, topic_followup, topic_preamble with context %}

{% call topic_preamble("OOP and UML Class/Object Diagrams: Inheritance", reuse=false) %}
**Let's learn the important OOP concept of _inheritance_** this week, together with how to show it in UML class diagrams.
{% endcall %}
<!-- ---------------------------------------------------------------------------- -->
{% call topic_preamble("UML Class/Object Diagrams: Composition, Aggregation, Dependencies", reuse=false) %}
**Next, we cover some additional class/object diagram notations** used to show different types of relationships in class/object diagrams.

{% endcall %}
<!-- ---------------------------------------------------------------------------- -->
{% call topic_followup("uml-classDiagrams-dependencies-what", reuse=false) %}
After learning the UML syntax in the section above, you can try the worked example given below. It's ==even better if you do the [Week 10 - Quiz (**Part I**)]({{ url_quizzes }})== (on Canvas) before watching the video below:<br>
{{ panopto("f4f7e1f2-60a4-4d18-b70a-ac4000f17608") }}

After watching the above example, you can try this exercise. The answer will be given during the following lecture.

<panel header="Exercise: Draw class/object diagrams for HouseManager code">
<include src="exercise-houseManagerUmlDiagrams-fragment.md" />
</panel>
<p/>
{% endcall %}
<!-- ---------------------------------------------------------------------------- -->
{% call topic_preamble("Types of Testing", reuse=false) %}
**Let's also have a brief look at various types of testing** that is done in software projects, as you will be learning how to do one of them using Python in this week too.
{% endcall %}
<!-- ---------------------------------------------------------------------------- -->
