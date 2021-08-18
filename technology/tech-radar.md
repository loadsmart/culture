---
title: Loadsmart Tech Radar
description: What tech we use and their state at Loadsmart
---

# Tech Radar

Loadsmart's Tech Radar is powered by Thoughtworks' open source [Build Your Own Radar](https://www.thoughtworks.com/radar/how-to-byor) tool. To learn more about the Tech Radar concept, visit [https://www.thoughtworks.com/radar](https://www.thoughtworks.com/radar).

Do you know of a tech we use and want to include it to this radar? Edit the [loadsmart-tech-radar.csv](loadsmart-tech-radar.csv) file and visit [this page](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fraw.githubusercontent.com%loadsmart%2Fculture%2Fmaster%2Ftechnology%2Floadsmart-tech-radar.csv).

If in doubt when adding a new entry, consider the explanation below taken from TW's website:

## Radar Structure

The Radar is all about tracking interesting things, which we refer to as blips. We organize the blips onto the Radar using two categorizing elements: the quadrants and the rings. The quadrants represent different kinds of blips. The rings indicate what stage in the adoption lifecycle we think they should be in.

## Blips

A blip is a technology or technique that plays a role in software development. Blips are things that are ‘in motion’ - that is we find their position in the Radar is changing - usually indicating that we’re finding increasing confidence in them as they move through the rings.

## Quadrants

The quadrants are a categorization of the type of blips:

- **Programming Languages and Frameworks**: Programming languages and frameworks used or being considered at Loadsmart
- **Tools**: These can be components, such as databases, software development tools, such as versions control systems; or more generic categories of tools, such as the notion of polyglot persistence.
- **Platforms**: Things that we build software on top of such as mobile technologies like Android, virtual platforms like the JVM, or generic kinds of platforms like hybrid clouds.
- **Techniques**: These include elements of a software development process, such as experience design; and ways of structuring software, such as microservices.

We don't make a big deal out of the quadrants - they’re really just a way to break up the Radar into topic areas. We don't think it's important which quadrant a blip goes into, unlike the rings - which generate a lot of discussion.

## Rings

The metaphor of a radar says that the closer a blip is to you, the sooner it will be on top of you. Like most metaphors, you can't take it too seriously, but there's an essential sense to it.

Our Radar has four rings, which we'll describe starting from the middle:

- The **Adopt** ring represents blips that we think you should seriously consider using. We don't say that you should use these for every project; any tool should only be used in an appropriate context. However we do think that a blip in the Adopt ring represents something where there's no doubt that it's proven and mature for use.
- The **Trial** ring is for blips that we think are ready for use, but not as completely proven as those in the Adopt ring. So for most organizations we think you should use these on a trial basis, to decide whether they should be part of your toolkit. Typically we've used trial blips in production, but we realize that readers are more cautious than us.
- The **Assess** ring are things to look at closely, but not necessarily trial yet - unless you think they would be a particularly good fit for you. Typically, blips in the Assess ring are things that we think are interesting and worth keeping an eye on.
- The **Hold** ring is for things that, even though they are accepted in the industry, we haven't had a good experience with. Therefore we are calling them out to warn you that you may run into trouble with them as well. Sometimes this is because we don't think they're mature enough yet; sometimes it means we think they're irredeemably flawed; or just being misused. We do place things in the Hold ring that we wish the industry wouldn't use.

Having said that, the order of the entries on the [CSV](./loadsmart-tech-radar.csv) file matters. The first entries for a given quadrant are the ones closer to the next center-most ring.
