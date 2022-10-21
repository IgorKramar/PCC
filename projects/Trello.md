# PCC Trello

## Introductory words

We all had to (or have to) face in our work with Kanban.Whether it be Trello, Asana, Jira or even a real physical board, you dragged these stickers from the column "in the work" in the column "made", feeling the pleasure of the work done.

> Kanban (Japanese: カンバン and Chinese: 看板, meaning signboard or billboard) is a scheduling system for lean manufacturing (also called just-in-time manufacturing, abbreviated JIT). Taiichi Ohno, an industrial engineer at Toyota, developed kanban to improve manufacturing efficiency. The system takes its name from the cards that track production within a factory. Kanban is also known as the Toyota nameplate system in the automotive industry.
> **Wikipedia**

For many years of the company, the company conducted physical accounting of stickers on a real board, but in 2011 to an excellent programmer and author [of an interesting book](https://archive.org/details/joelonsoftwareon00spol) Joel Spolski occurred to transfer this process to web. So Trello was born.

## Need
Imagine that this thought has not visited Joel's bright head. But the need for such an application is in the air. Let's think that we would like from this application.

- First of all, the board itself, which will become the basis for our kanban process.
- The board should be divided into columns, we can create new columns, remove the old ones, rename them and change the speakers in places.
- In each column, we have cards (stickers), which are presented in the column, for our first MVP, let them contain just the text that we see in the sticker.
- These cards can be moved from one column to another, added or removed.
- Oh yes, perhaps we will need several boards for different projects or parts of the project, so we want to see a list of boards, we want to add new boards, remove old ones or rename the existing ones.

So, we have a simple hierarchical structure - App > Board> Column> Card.

Let's start with this and try to sketch our first backend and frontend for our Perfect Clone!
