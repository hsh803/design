---
title: "Test"

views:

    flash:
        region: flash
        template: anax/v2/image/default
        data:
            src: "image/code.png?width=100%&height=150&crop-to-fit"

    redovisa:
        region: sidebar-left
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa

    kursrepo:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-kursrepo
---
Test i kursen design
=========================
You can find the file of this page on `content/test.md`.
