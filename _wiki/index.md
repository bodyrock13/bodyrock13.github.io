---
layout  : wikiindex
title   : wiki
toc     : true
public  : true
comment : false
regenerate: true
---

## 도서

* [[the-book-of-genesis]]{창세기와 만나다}
* [[art-of-thingking-clearly]]{스마트한 생각들}
* [[swing-wa-nai]]{의미가 없다며 스윙은 없다(무라카미 하루키)}

---

## blog posts
<div>
    <ul>
{% for post in site.posts %}
    {% if post.public != false %}
        <li>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
                {{ post.title }}
            </a>
        </li>
    {% endif %}
{% endfor %}
    </ul>
</div>

