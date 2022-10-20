---
date: 2022-10-19T16:38
---

# Mithril

Use [flems.io](http://flems.io) to create prototypes:
- [mardown example](https://flems.io/#0=N4IgtglgJlA2CmIBcAWFA6A7AGhAZ3gQGMAXeKZEdACxLFhFwDMIE9kBtUAOwEMxESKrXqMQRAPbcy0ygB4oEAG4ACaAF4AOuCjaAfCs3cAxCurxeuk6bwBXAEZGjeCQJUB9MBIBO8dyrIADxIVXm4oFRc3ACpo+wlYKFiA+GDDbgBaFXgAcwBPIyyAa3gSEglCs15vV0ruXILuAAMWoyIIgD8AegAHbwArLqjyCG8jWDwVDNheIyYfNTVuFWAABnR0AE4AXwBuFSgK5ZVsomoJFXUrlQASCCND+qMWpqM5LsUlPTECYhIIKTsIQARhQqBA22wPH4gio-XYuEk0ngsiERjAUHUhyItgE0nQOVKAFEEHiSAAhPIASSgAAptBjtABKdBBEgAYSkMhI6PQvnC8G8tOxuJRJHQ8SgeWwKjArO8tjwJFpYGqJSg6B61QIKqgTP1P0I8FIAO4QJAwNQKAhUJAfAElHQRDwCPEXLFlAhAF1cLAINwikCuHaYZRVd51WJbN4GEJaCQengkF0urZuD0ijkna4uuH1QABDDA9DArp++y5tXkdC4jXwsQkPI9WF4IjeCA9Eg26EOoSQEjUdsMXDR2MgeOJ5Op9OZ7NgXMQAdD-MAJnQa5XC6XrHQkG46HruEbzcorfbne9uHtsLzhwA7twIUA)

You can embed editables examples like:

```{=html}
<div id="example1" style="height: 200px;"></div>
<script src="https://flems.io/flems.html" type="text/javascript" charset="utf-8"></script>
<script>
const flems = Flems(example1, {
    files: [{
        name: 'app.js',
        content: 'm.render(document.body, m("h1", "Hello world"))'
    }],
    links: [{
        name: 'mithril',
        type: 'script',
        url: 'https://unpkg.com/mithril'
    }]
})
</script>
```

## Css customization

you can use tailwind  here:

## Highlights of the day:

:::{.rounded .shadow-2xl .border-2 .border-solid .border-pink-400 .text-xl .mb-4}
- Drank a [new]{.my-highlight} type of *coffee*
- Hacked a new feature to my pet project
- Enjoyed doing nothing in particular
:::
