# Albasani Project Repositories

## History of Albasani

The late Alexander Bartolich (the "Alba" part of "Albasani") was a very active participant in all things Usenet: operator of *news.albasani.net*, member of the [*Big 8 Management Board*](https://www.big-8.org/wiki/Board_members), "Umsetzungsbeauftragter" ("control guy") of the [*Moderation of de.admin.news.announce*](https://dana.de/) (roughly the counterpart of the Big 8 Board for the German language Usenet hierachy de.\*) and more.

His early death came as a shock to the Usenet community.

* [Statement of the *Big 8 Management Board*](https://groups.google.com/g/news.announce.important/c/zXWgY-Ng56Y) in *news.announce.important*
* [Statement of the *Moderation of de.admin.news.announce*](https://groups.google.com/g/de.admin.news.announce/c/5mUSjsjrqqI) in *de.admin.news.announce*

Unfortunately, his technical legacy was mostly lost as *news.albasani.net* finally went down after a hardware failure in 2020. The same machine was hosting some software repositories at `svn.schnuerpel.eu` that were - to the best of my knowledge - not mirrored elsewhere, containing enhancements to the *INN* software running on *news.albasani.net* (namend "Schnuerpel") and a web application to moderate Usenet newsgroups (named "Huhu").

I had downloaded (`snv checkout`) the repositories on 2012-07-18, about a week after we lost Alexander, but got just the files, not the history, as is typical for *SVN* repositories (in contrast to *git*). As the complete repositories couldn't be recovered until today, I'll upload the shallow clones here to share what I was able to preserve.

## Repositories

(Yes, the names are as nonsensical in German as they sound in English. That was the point, I think.)

### [Schnuerpel](https://github.com/Albasani/Schnuerpel)

> Authentication, access rights, cancel locks, etc. (INN 2.4 or newer)

Quoting from the README:

> Schnuerpel is a collection of scripts used on server news.albasani.net.
>
> [...]
> Since Schnuerpel is not a monolithic piece of software it is quite
> possible to use only selected parts or disable optional features,
> e.g. mysql.
> 
> Scripts can be categorized into three groups according to the
> environment they are used in:
> 
> - plain command line
> - scheduled invocation through crond
> - event triggered invocation by INN (access control, filters)

### [Huhu](https://github.com/Albasani/Huhu)

> Web application to moderate Usenet groups.

Quoting from the documentation:

> Huhu is a web application to moderate Usenet groups.
>
> [...]
>
> Roman Racine developed Huhu in 2007 to moderate de.soc.familie.vaeter.  
> In 2009 he adapted it to easily run multiple instances.  
> In autumn 2009 Alexander Bartolich took over development, adding support for CSS, multiple languages, and procmail.

### [giglgu](https://github.com/Albasani/giglgu)

I really have no idea what this project is about.
