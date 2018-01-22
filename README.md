# Problem statement

The internet is full of software and source code. Some of that software is
actively developed, some is mature but receives security updates and other
infrequent changes and a lot of it is abandonware or one-off demo.

As software developers you have both a responsibility and a duty to your fellow
developers to clearly state if something is supported or not. It's always
annoying to find that one of your dependencies is no longer maintained.

# Project Status

Wouldn't it be great if it was easy to clearly and unambiguously state that a
project is no longer supported or that conversely it is actively supported?
Enter *project status*. We supply you with an easy-to-use badge that documents
how the author or principal maintainer sees a given repository.

## Abandoned

The project may have been great once or it may have been just a demo. In either
case it is not actively maintained. If you have it as a dependency then
immediately migrate to another project.

## SecurityOnly/{Year}

The project is not actively developed and the maintainers may only apply
security fixes. If you have it as a dependency you can keep using it but
consider migration to another dependency.

The {year} indicates when the project was last updated for security fixes.

## Maintained/{Year}

The project is not actively actively developed but maintainers are responsive
and wish to keep the software reliable and secure.

The {year} indicates when the project was last updated.

## Lively/Stable

The project is actively developed and should offers a solid base for other
software. It is past its early development stages and can be used by third
parties. Maintainers are working periodic new releases.

## Lively/Unstable

The project is actively evolving and may be the next big thing but at this
moment only early adopters are welcome. Maintainers are working on new features
but don't plan to make new releases that can be used as a stable base just yet.
