# Learning Adventure content

Public educational content for the parent-supervised Learning Adventure preview,
grades 3-5: math, science, social studies and English. App source remains in the
owner's separate private repository. This repository contains no child accounts,
learning progress, private signing keys or application source.

The initial version 2 library contains 162 draft lessons and 3,324 bank questions:
84 unchanged authored pilot questions, 2,430 structured tasks from 810 original
cases, and 810 generated math items. Each grade has 282 math, 276 science, 276
social-studies and 274 English questions.

## Download in the app

App build 2 and later support **Parent corner > Signed lesson updates > Check and
download new lessons**. Compatible content can be updated without reinstalling the
APK or Windows app. Downloaded lessons work offline.

Releases contain a signed manifest and twelve grade/subject packs. The app verifies
the signature against its pinned public key, then checks pack hashes, sizes and
schema before saving the whole library. A signature identifies the publisher;
it does not certify educational correctness. The app can restore bundled lessons
or a previous verified download when available.

The initial online version may match the bundled library. The maintainer must
publish a newer compatible version to add material; the library does not grow
automatically and does not generate online AI answers for children.

## Draft content and privacy

All concepts, examples, FAQ, questions and suggested Foundations/US/India pathway
mappings await educator review. The pathways are topic groupings, not complete or
certified curricula. Structured and numerical practice variants are labeled as
generated, not counted as independently authored lessons.

The app contacts GitHub for content only after a parent presses the download
button. GitHub receives ordinary network metadata, never learner progress.
Learning records remain on the device.

Install packages and the stable Android QR are in the separate
[download repository](https://github.com/kish14all/learningadventure-releases).
No open-source or broad content-reuse license has been selected for this preview.
