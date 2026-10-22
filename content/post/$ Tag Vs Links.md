---
title: $ Tag Vs Links
date: 2026-08-26 09:02:00
lastmod: 2026-10-21 14:50:42
categories: []
tags:
  - MOC
  - knowledge-management
  - obsidian
  - tags-vs-links
aliases:
  - Tag Vs Links
share: true
editcount: 3
rating:
readnow: false
relevantloc:
---

# $ Tag Vs Links

> [!NOTE] BLUF
> *What is MOC (to you)?*

**Back link to (sub)Area(s):** [Knowledge Management]({{< ref "$ Knowledge Management" >}})
Key-Related:: [Obsidian]({{< ref "$ Obsidian" >}}) | [$ Tags]({{< ref "$ Tags" >}}) | [$ Links]({{< ref "$ Links" >}})

**Bases query on `#tags-vs-links`**

*So this is a topic without a useful query tag…*

```base
filters:
  and:
    - file.hasTag("tags-vs-links")
    - file.path != this.file.path

views:
  - type: table
    name: Tags
    order:
      - file.name
      - file.path
```

**Tags** are "universal" [Binding]({{< ref "$ (Re)binding" >}}) points (in a ~~global~~ unbounded/unspecified [Namespace]({{< ref "$ Name Systems#Name Spaces" >}})) that are simply a field in an application (i.e. a [database]({{< ref "$ Databases - MOC" >}})) with the (soft) assignment of being so. *That is, it's effectively an array of strings for some [Linker]({{< ref "$ Scrapers" >}}) to build associations.* In that way, they can be used to label data very freely; Any more constrained/controlled behavior calls for the building of a [Type]({{< ref "_Types" >}}) in the [Programming System]({{< ref "Programming" >}}) of choice. ^[perhaps all programming languages plug into the operating systems database to create 'native' datatypes and schemas for controlling namespaces?]

**Links** are addresses that serve a similar role to tags, but for binding **particular** elements (i.e. records/indexes) in a database. They give more granular **pathes** to traverse, generating webs that elicit **ontologies** by consequence.

↪ *Heck, **Links** merely [Bind]({{< ref "$ (Re)binding" >}}) to a field (namely, the **title** of the note)*

## Key-References

### Projects

*related projects*

### Resources

*related resources*

1. [Links Vs Tags]({{< ref "Links Vs Tags" >}})

### Clippings

*related clippings (references?)*

## Random Capture

**2026-10-16 11:30:37 - aidev**

![$ Tags As Concepts#^c84fc3](/images/$ Tags As Concepts#^c84fc3)

I think links are remarkable in that **they create paths**. Paths are an element of [$ Graph Theory]({{< ref "$ Graph Theory" >}}) and the remarkable ideas surrounding [$ Memex]({{< ref "$ Memex" >}})! ==So then think of these [computer system]({{< ref "$ Computer Systems MOC" >}}) components from their [First Prinicples]({{< ref "$ First Principles" >}}) and see how their usage builds meaning! [$ Rhetoric]({{< ref "$ Rhetoric" >}})==

## Start Here

*>> Links to related notes <<*

*Think about it, a MOC is a discussion board of sorts. You want to aggregate the resources to do with said topic. You will have resources you constantly want to reference (perhaps a FAQ?)*

*What are questions you find yourself asking over and over? Does it make sense to point to a whole tutorial? Well, maybe at least citing the source (tutorial) of an answer given.*

### FAQ

### Sub-Topics
