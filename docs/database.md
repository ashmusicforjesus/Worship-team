# Worship Team Database v1.0

## Team

Fields:

- id
- name
- createdBy
- createdAt

---

## User

Fields:

- id
- displayName
- email
- role
- approved
- teamId

Roles:

- owner
- admin
- member

---

## Song

Fields:

- id
- title
- artist
- key
- tempo
- content
- tags
- favorite
- pinned
- createdBy
- updatedAt

---

## Setlist

Fields:

- id
- name
- date
- songIds

---

## Assignment

Fields:

- id
- setlistId
- songId

Assignments:

- leadVocal
- backupVocal
- electricGuitar
- acousticGuitar
- bass
- keyboard
- drums

---

## Announcement

Fields:

- id
- title
- message
- createdBy
- createdAt

---

## Chat

Fields:

- id
- channel
- message
- createdBy
- createdAt

Channels:

- general
- musicians
- vocalists
