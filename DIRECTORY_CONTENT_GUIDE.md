# Detailed Directory Content Guide

This file documents the current organized directory as it exists now: **9 subject folders containing 43 LaTeX project folders**. Each entry below describes one project/document folder, identifies its main `.tex` file, and explains the content based on the actual title blocks, section headings, visible text, and supporting assets inside the project.

## Scope and Reading Method

- Unit of description: each child project folder inside the subject directories.
- Main source file: the most likely entrypoint `.tex` file for each project (usually `main.tex`, but some projects use `Reporte01.tex` or `demo.tex`).
- Description style: factual where the content is explicit, and interpretive where the document is mostly exercises, screenshots, or sparse sectioning.
- Asset counts matter here because several projects are mostly composed of diagrams or screenshot-based answers rather than long prose.

## Directory Summary

- `algoritmos-y-matematicas`: 3 projects. Projects in this folder lean toward proofs, discrete structures, graph problems, and mathematically framed exercises.
- `arquitectura-y-sistemas-operativos`: 3 projects. This group mixes hardware-oriented laboratory work with systems-level operating system analysis.
- `bases-de-datos`: 12 projects. This is the largest group and spans the whole databases pipeline: concepts, ER design, relational modeling, normalization, exams, and physical SQL implementation.
- `computacion-distribuida`: 7 projects. These documents are mostly proof-oriented distributed computing assignments about processes, messages, failures, clocks, and consistency.
- `criptografia-y-seguridad`: 1 project. This folder contains a focused cryptography assignment with both proof and protocol-analysis components.
- `geoquimica-organica`: 2 projects. These are science-course documents outside the main CS track, centered on organic geochemistry.
- `inteligencia-artificial`: 2 projects. The AI folder contains project reports with agent design, environment modeling, and implementation planning.
- `intro-programacion-y-logica`: 8 projects. This group blends introductory programming, language theory, formal logic, and digital logic exercises.
- `redes`: 5 projects. The networking folder includes both infrastructure reports and more conceptual summaries and presentations.

## algoritmos-y-matematicas

Projects in this folder lean toward proofs, discrete structures, graph problems, and mathematically framed exercises.

### Examen

- Folder: `algoritmos-y-matematicas/Examen`
- Main document: `algoritmos-y-matematicas/Examen/main.tex`
- Visible title: `Examen`
- Author line(s): `iabin Arteaga`
- Date line(s): `February 2022`
- LaTeX footprint: 1 `.tex` file(s), 0 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a very short mathematics exam write-up centered on a combinatorial sum with binomial coefficients. The document sets up a single problem, defines the binomial coefficient explicitly, and reads like the start of a worked derivation rather than a full solved exam packet.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Problema 1`.

**What To Expect If You Open It**
Expect a mostly text-only document with little reliance on figures.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Protocolo

- Folder: `algoritmos-y-matematicas/Protocolo`
- Main document: `algoritmos-y-matematicas/Protocolo/main.tex`
- Visible title: `El problema del clique máximo`
- Author line(s): `Arteaga Hernández Alejandro Iabin`
- Date line(s): `UNAM Diciembre 2017`
- LaTeX footprint: 1 `.tex` file(s), 0 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This document is a research-style protocol or proposal about the maximum clique problem. It explains the problem in graph-theoretic terms, gives background on exact algorithms and complexity, states a hypothesis about using a genetic algorithm with elitism and local search, and closes with a methodology based on DIMACS benchmarks and comparative evaluation.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Introducción`, `Hipótesis`, `Metodología`.

**What To Expect If You Open It**
Expect a mostly text-only document with little reliance on figures.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Tarea Galadios

- Folder: `algoritmos-y-matematicas/Tarea Galadios`
- Main document: `algoritmos-y-matematicas/Tarea Galadios/main.tex`
- Visible title: `Tarea Galadios`
- Author line(s): `iabin Arteaga`
- Date line(s): `May 2019`
- LaTeX footprint: 1 `.tex` file(s), 1 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a brief exercise sheet focused on discrete mathematics or elementary number theory. The visible content includes a modular arithmetic or discrete logarithm style exercise in a finite field, followed by a minimal conclusion, so it feels more like a compact answer submission than a developed report.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Ejercicios`, `Conclusion`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

## arquitectura-y-sistemas-operativos

This group mixes hardware-oriented laboratory work with systems-level operating system analysis.

### Arqui

- Folder: `arquitectura-y-sistemas-operativos/Arqui`
- Main document: `arquitectura-y-sistemas-operativos/Arqui/main.tex`
- Visible title: `Organización y Arquitectura de computadoras Práctica 1`
- Author line(s): `Arteaga Hernández Alejandro Iabin 313033414`
- Date line(s): `18 de febrero de 2017`
- LaTeX footprint: 1 `.tex` file(s), 5 image asset(s), 0 bibliography file(s), 1 PDF asset(s).

**Content Explanation**
This is a hardware and computer architecture lab report. The content points to collecting machine specifications, timing experiments, normalized execution times, and qualitative performance discussion, with several images and attachments supporting the measurements and conclusions.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Investigación de Android 

- Folder: `arquitectura-y-sistemas-operativos/Investigación de Android `
- Main document: `arquitectura-y-sistemas-operativos/Investigación de Android /main.tex`
- Visible title: `Universidad Nacional Autónoma de México / Facultad de Ciencias / Sistemas Operativos 2018-2 / Android`
- Author line(s): `Profesor Salvador López Mendoza / Alumnos: Grupo 1`
- Date line(s): `7 de junio de 2018`
- LaTeX footprint: 1 `.tex` file(s), 7 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is an operating-systems research report on Android. It surveys Android from the kernel upward: architecture, Linux underpinnings, process model, wake locks, out-of-memory handling, Dalvik, Binder IPC, application components, intents, and sandboxing, making it one of the most conceptually broad documents in the directory.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Introduction`, `Temario`, `Arquitectura`, `Extensiones. Wake locks`, `Extensiones. Out-of-memory killer`, `Dalvik`, `Binder IPC. Binder kernel module`, `Binder IPC. Binder userspace IPC; interfaces and AIDL`, `Aplicaciones en Android`, `Aplicaciones en Android. Actividades`.
The document continues beyond those headings, for a total of 17 detected section-level markers.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### reies

- Folder: `arquitectura-y-sistemas-operativos/reies`
- Main document: `arquitectura-y-sistemas-operativos/reies/main.tex`
- Visible title: `Organización y Arquitectura de computadoras Práctica 1`
- Author line(s): `José Fernando Reyes García`
- Date line(s): `18 de febrero de 2017`
- LaTeX footprint: 1 `.tex` file(s), 0 image asset(s), 0 bibliography file(s), 1 PDF asset(s).

**Content Explanation**
This appears to be a parallel or alternate submission of the same architecture practice represented by `Arqui`, likely from a different teammate. It focuses on machine characteristics, memory/CPU information, timing, and performance-oriented observations rather than theoretical exposition.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-only document with little reliance on figures.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

## bases-de-datos

This is the largest group and spans the whole databases pipeline: concepts, ER design, relational modeling, normalization, exams, and physical SQL implementation.

### Bitacora 1

- Folder: `bases-de-datos/Bitacora 1`
- Main document: `bases-de-datos/Bitacora 1/main.tex`
- Visible title: `Facultad de Ciencias. / Tarea 6 / Fundamentos de Bases de Datos.`
- Author line(s): `Arteaga Hernández Alejandro Iabin`
- Date line(s): `Entrega 22 de Mayo 2020`
- LaTeX footprint: 1 `.tex` file(s), 21 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
Despite the folder name, this document is titled as `Tarea 6` for Fundamentos de Bases de Datos. The file looks implementation-heavy: keyword evidence and the large number of screenshots suggest SQL schema creation, table definitions, primary/foreign keys, and visual evidence of the resulting database state or execution results.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a visually dense document with many embedded diagrams or screenshots alongside the written explanation.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Examen 2

- Folder: `bases-de-datos/Examen 2`
- Main document: `bases-de-datos/Examen 2/main.tex`
- Visible title: `Facultad de Ciencias. / Examen Parcial 2. / Fundamentos de Bases de Datos.`
- Author line(s): `Arteaga Hernández Alejandro Iabin Barocio Gómez Luis Fernando Ledesma Granados Roberto Andrés Castrejón Estrada Juan Carlos`
- Date line(s): `Entrega 28 de Abril 2020`
- LaTeX footprint: 1 `.tex` file(s), 6 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a database midterm-style document with many worked items and supporting diagrams. The keywords strongly suggest classic relational modeling and querying exercises, likely using bar/beer/drinker-style examples to reason about relations, information content, and SQL or relational algebra queries.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Practica 1 FBD

- Folder: `bases-de-datos/Practica 1 FBD`
- Main document: `bases-de-datos/Practica 1 FBD/main.tex`
- Visible title: `Facultad de Ciencias / Practica 1 / Fundamentos de Bases de Datos`
- Author line(s): `Arteaga Hérnandez Alejandro Iabin Barocio Gómez Luis Fernando`
- Date line(s): `Fecha de entrega: 19 Febrero 2020`
- LaTeX footprint: 1 `.tex` file(s), 5 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is an introductory databases lab. The first half is a setup or installation guide, while the second half answers conceptual questions about database engines and data management, including SQL vs. NoSQL themes, practical use cases, and tooling choices.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Manual de instalación`, `Preguntas`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Tarea 01

- Folder: `bases-de-datos/Tarea 01`
- Main document: `bases-de-datos/Tarea 01/main.tex`
- Visible title: `Tarea 1: Conceptos Básicos`
- Author line(s): `Alejandro Iabin Arteaga Hernández Barocio Gómez Luis Fernando`
- Date line(s): `Febrero 2020`
- LaTeX footprint: 1 `.tex` file(s), 0 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This assignment is a foundations survey for databases. It reviews core concepts and then moves into data conversion, consolidation, manual entry, batch feeds, real-time interfaces, cleaning, purging, system upgrades, and process automation, so the document reads like both a theory review and a data lifecycle overview.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Conceptos generales`, `Lectura`, `Initial Data conversion`, `System consolidations`, `Manual Data Entry`, `Batch Feeds`, `Real Time Interfaces`, `Data Processing`, `Data Cleaning`, `Data Purging`.
The document continues beyond those headings, for a total of 17 detected section-level markers.

**What To Expect If You Open It**
Expect a mostly text-only document with little reliance on figures.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Tarea 02 Bases

- Folder: `bases-de-datos/Tarea 02 Bases`
- Main document: `bases-de-datos/Tarea 02 Bases/main.tex`
- Visible title: `Tarea 2: Modelo Entidad – Relación`
- Author line(s): `Arteaga Hernández Alejandro Iabin Barocio Gomez Luis Fernando Castrejón Estrada Juan Carlos Ledesma Granados Roberto Andrés`
- Date line(s): `Marzo 2020`
- LaTeX footprint: 1 `.tex` file(s), 9 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is the entity-relationship modeling assignment. It begins with concept review, then develops an ER model, and includes an inverse-engineering component, so the document is about translating requirements into entities, relationships, and attributes with justification.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Repaso de conceptos generales`, `Modelo Entidad/Relación`, `Ingeniería inversa`, `Referencias`.

**What To Expect If You Open It**
Expect a visually dense document with many embedded diagrams or screenshots alongside the written explanation.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Tarea 03 bases

- Folder: `bases-de-datos/Tarea 03 bases`
- Main document: `bases-de-datos/Tarea 03 bases/main.tex`
- Visible title: `Tarea 3: Modelo Relacional`
- Author line(s): `Arteaga Hernández Alejandro Iabin Barocio Gomez Luis Fernando Castrejón Estrada Juan Carlos Ledesma Granados Roberto Andrés`
- Date line(s): `Abril 2020`
- LaTeX footprint: 1 `.tex` file(s), 7 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This document moves from ER thinking into the relational model. It covers review questions, relational schema design, tuple insertion, and integrity constraints, making it a bridge between conceptual design and table-level formalization.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Preguntas de repaso`, `Modelo relacional`, `Modelo relacional e inserción de tuplas`, `Modelo relaciones y restricciones de integridad`, `Referencias`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Tarea 04 Bases de Datos

- Folder: `bases-de-datos/Tarea 04 Bases de Datos`
- Main document: `bases-de-datos/Tarea 04 Bases de Datos/main.tex`
- Visible title: `Facultad de Ciencias. / Tarea 4. / Fundamentos de Bases de Datos.`
- Author line(s): `Arteaga Hernández Alejandro Iabin Barocio Gómez Luis Fernando`
- Date line(s): `Fecha entrega 5 de Abril de 2020`
- LaTeX footprint: 2 `.tex` file(s), 27 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This assignment looks like a heavily diagrammed database design exercise over a banking-style domain. The keywords mention customers, branches, accounts, loans, balances, and borrowers, and the large number of images suggests ER diagrams, schema illustrations, or handwritten/annotated solutions embedded as figures.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a visually dense document with many embedded diagrams or screenshots alongside the written explanation.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Tarea 5 fbd

- Folder: `bases-de-datos/Tarea 5 fbd`
- Main document: `bases-de-datos/Tarea 5 fbd/main.tex`
- Visible title: `Facultad de Ciencias. / Tarea 5 / Fundamentos de Bases de Datos.`
- Author line(s): `Arteaga Hernández Alejandro Iabin Barocio Gómez Luis Fernando Ledesma Granados Roberto Andrés Castrejón Estrada Juan Carlos`
- Date line(s): `Entrega 4 de Mayo 2020`
- LaTeX footprint: 1 `.tex` file(s), 0 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a normalization and dependency-theory assignment. It works with functional dependencies, closures, candidate keys, superkeys, and normal forms such as BCNF and 3NF, so the emphasis is on proving whether a schema is well-designed and decomposing it when it is not.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-only document with little reliance on figures.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Tarea 6

- Folder: `bases-de-datos/Tarea 6`
- Main document: `bases-de-datos/Tarea 6/main.tex`
- Visible title: `Facultad de Ciencias. / Tarea 6 / Fundamentos de Bases de Datos.`
- Author line(s): `Arteaga Hernández Alejandro Iabin Barocio Gómez Luis Fernando Ledesma Granados Roberto Andrés Castrejón Estrada Juan Carlos`
- Date line(s): `Entrega 22 de Mayo 2020`
- LaTeX footprint: 1 `.tex` file(s), 21 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is the more implementation-oriented continuation of the database sequence. The keywords indicate explicit SQL DDL work: `CREATE TABLE`, data types, primary keys, foreign keys, and model realization, so it appears to document the physical schema corresponding to an earlier logical design.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a visually dense document with many embedded diagrams or screenshots alongside the written explanation.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### TareaExamen 1

- Folder: `bases-de-datos/TareaExamen 1`
- Main document: `bases-de-datos/TareaExamen 1/main.tex`
- Visible title: `Facultad de Ciencias / Tarea-Examen 1 / Fundamentos de Bases de Datos`
- Author line(s): `Arteaga Hérnandez Alejandro Iabin Barocio Gómez Luis Fernando`
- Date line(s): `Fecha de entrega: 13 Marzo 2020`
- LaTeX footprint: 1 `.tex` file(s), 24 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is an exam-style database assignment combining theory and design. It includes questions about abstraction levels, ER equivalence, and redesigning a schema to capture richer facts such as prescriptions and dates, so it is more analytical than purely mechanical.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a visually dense document with many embedded diagrams or screenshots alongside the written explanation.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### diseño

- Folder: `bases-de-datos/diseño`
- Main document: `bases-de-datos/diseño/main.tex`
- Visible title: `Diseño de la base de datos`
- Author line(s): `Alejandro Iabin Arteaga Hernández`
- Date line(s): `Diciembre 2019`
- LaTeX footprint: 1 `.tex` file(s), 3 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a database design rationale document. It explains the ER model, justifies relationships, then translates the design into a relational model while defending decisions such as introducing surrogate keys and splitting multivalued attributes into more normalized structures.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Modelo Entidad - Relación`, `Justificación de las relaciones`, `Modelo Relacional`, `Modelo relacional, justificación`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### normalizacion

- Folder: `bases-de-datos/normalizacion`
- Main document: `bases-de-datos/normalizacion/main.tex`
- Visible title: `Normalizacion`
- Author line(s): `Alejandro Iabin Arteaga Hernández`
- Date line(s): `Diciembre 2019`
- LaTeX footprint: 1 `.tex` file(s), 4 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This report is a direct walkthrough of normalization. It starts with an unnormalized relational design and then shows how it evolves through 1NF, 2NF, and 3NF, explicitly tying the changes to functional dependencies and redundancy elimination.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Modelo relacional sin normalizar`, `Primera forma normal`, `Segunda Forma Normal`, `Tercera Forma Normal`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

## computacion-distribuida

These documents are mostly proof-oriented distributed computing assignments about processes, messages, failures, clocks, and consistency.

### Tarea01 distribuida

- Folder: `computacion-distribuida/Tarea01 distribuida`
- Main document: `computacion-distribuida/Tarea01 distribuida/main.tex`
- Visible title: `Tarea 1 Computación distribuida`
- Author line(s): `Arteaga Hernández Alejandro Iabin \ / Olea Olvera Marco`
- Date line(s): `Agosto 2019`
- LaTeX footprint: 1 `.tex` file(s), 1 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is an early distributed computing homework focused on message-passing behavior in networks of processes. The vocabulary suggests a protocol over neighbors, ordered message dissemination, and reasoning about what each process receives and forwards.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### Tarea02_Distribuida

- Folder: `computacion-distribuida/Tarea02_Distribuida`
- Main document: `computacion-distribuida/Tarea02_Distribuida/main.tex`
- Visible title: `Computación Distribuida / Tarea 02`
- Author line(s): `Olea Olvera Marco Iván / Arteaga Hernández Labín`
- LaTeX footprint: 1 `.tex` file(s), 1 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This homework appears to analyze a tree-structured or rooted distributed algorithm. Terms like `parent`, `children`, `neighbors`, and population/message bookkeeping suggest a protocol that builds or reasons over a communication tree and tracks what has been sent or received.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Tarea03_Distribuida

- Folder: `computacion-distribuida/Tarea03_Distribuida`
- Main document: `computacion-distribuida/Tarea03_Distribuida/main.tex`
- Visible title: `Computación Distribuida / Tarea 03`
- Author line(s): `Olea Olvera Marco Iván / Arteaga Hernández Iabin`
- LaTeX footprint: 1 `.tex` file(s), 0 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This document is centered on correctness under faults and rounds. The text discusses processes failing after partial sends, decision values, and termination bounds, so the assignment is likely about broadcast, consensus, or agreement arguments in the presence of crash failures.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-only document with little reliance on figures.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Tarea04_Distribuida

- Folder: `computacion-distribuida/Tarea04_Distribuida`
- Main document: `computacion-distribuida/Tarea04_Distribuida/main.tex`
- Visible title: `Computación Distribuida / Tarea 04`
- Author line(s): `Olea Olvera Marco Iván / Arteaga Hernández Alejandro Iabin`
- LaTeX footprint: 1 `.tex` file(s), 1 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This homework is about impossibility or lower-bound style reasoning in unreliable distributed systems. The main argument revolves around message confirmations, uncertainty about delivery, and why agreement cannot be guaranteed under the stated communication model.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Tarea06_Distribuida

- Folder: `computacion-distribuida/Tarea06_Distribuida`
- Main document: `computacion-distribuida/Tarea06_Distribuida/main.tex`
- Visible title: `Computación Distribuida / Tarea 06`
- Author line(s): `Olea Olvera Marco Iván / Arteaga Hernández Alejandro Iabin`
- LaTeX footprint: 1 `.tex` file(s), 0 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This assignment focuses on causality and global states in distributed computation. The text explicitly references vector clocks, happened-before reasoning, and maximal consistent cuts, making it a proof-oriented homework on formal distributed-system semantics.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-only document with little reliance on figures.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Tarea5 distribuida

- Folder: `computacion-distribuida/Tarea5 distribuida`
- Main document: `computacion-distribuida/Tarea5 distribuida/main.tex`
- Visible title: `Computación Distribuida / Tarea 05`
- Author line(s): `Olea Olvera Marco Iván / Arteaga Hernández Alejandro Iabin`
- LaTeX footprint: 1 `.tex` file(s), 1 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This document appears to study logical time, message delay, and event ordering. The keywords and diagrams suggest reasoning with logical clocks or temporal bounds, probably through worked examples involving messages in transit and the latest possible event times.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### resumen4

- Folder: `computacion-distribuida/resumen4`
- Main document: `computacion-distribuida/resumen4/main.tex`
- Visible title: no formal `\title{}` found; the document appears to use a custom cover/title block.
- LaTeX footprint: 1 `.tex` file(s), 0 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is an English-language technical summary of high-performance computing. It explains parallelism, cluster architecture, MPI, cloud HPC, RDMA networking, and sector-specific use cases, so it functions more like a reading summary or study note on large-scale parallel systems than a homework proof set.

**Structural Cues**
The section/chapter structure points to the following internal organization: `How does HPC work?`, `Massively parallel computing`, `Computer clusters (also called HPC clusters)`, `High-performance components`, `Message passing interface (MPI)`, `HPC versus quantum computing`, `HPC and cloud computing`, `Surging demand`, `Prevalence of lower-latency, higher-throughput RDMA networking`, `Widespread public-cloud and private-cloud HPCaaS availability`.
The document continues beyond those headings, for a total of 19 detected section-level markers.

**What To Expect If You Open It**
Expect a mostly text-only document with little reliance on figures.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

## criptografia-y-seguridad

This folder contains a focused cryptography assignment with both proof and protocol-analysis components.

### Tarea 1 - Criptografía y Seguridad

- Folder: `criptografia-y-seguridad/Tarea 1 - Criptografía y Seguridad`
- Main document: `criptografia-y-seguridad/Tarea 1 - Criptografía y Seguridad/main.tex`
- Visible title: `FCiencias`
- LaTeX footprint: 1 `.tex` file(s), 2 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a substantial classical cryptography problem set. It includes proofs, key-space and brute-force calculations, XOR exercises, perfect secrecy questions, Vigenere analysis, monoalphabetic substitution, a modified one-time pad, a threshold-style key-splitting problem, and a private voting protocol.

**Structural Cues**
The section/chapter structure points to the following internal organization: `1. Demuestra lo siguiente:`, `2. Alicia y Bartolo escogen un espacio de claves de $ K`, `3. Combina las siguientes parejas de ńumeros usando la operacíon de XOR a nivel de bits.\ / a) Cadenas de bits: 1100110010, 0100010001.\ / b) Ńumeros decimales: 8191, 16383.\ / c) Cadenas de bytes: 0x23ab873f, 0x1a003dfb. (Los śımbolos 0x solo son para indicar que es hexadecimal.)`, `4. ¿Los siguientes esquemas de cifrado son perfectamente seguros? Explica.`, `5. Sea $ $ el esquema de Vigenere, donde $ M`, `6. Considera el criptosistema de sustitucíon monoalfab́etica con los siguientes cambios: $ M = C = ALF^ l`, `7. Definimos $ $ como una versión modificada de One-Time Pad`, `8. Sea $ $ un esquema de cifrado perfectamente seguro con un espacio de llaves $ K`, `9.Considera el siguiente escenario sobre una votación. Se tienen t votantes, y cada uno puede votar 0 o 1. Al final de la votacíon una persona anuncia el resultado S, que corresponde a la suma de todos los votos. Para llevar a cabo la votacíon de forma que ninǵun votante sepa nada m ́as que el resultado S, se propone el siguiente protocolo.\ / \ / Sea n > t un entero. Al inicio de la votacíon el encargado genera $c_0 <= $\ 0, 1, . . . n−1\`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

## geoquimica-organica

These are science-course documents outside the main CS track, centered on organic geochemistry.

### Examen 2 (Copy)

- Folder: `geoquimica-organica/Examen 2 (Copy)`
- Main document: `geoquimica-organica/Examen 2 (Copy)/main.tex`
- Visible title: `Facultad de Ciencias. / Bitácora 1 / Geoquímica orgánica`
- Author line(s): `Arteaga Hernández Alejandro Iabin`
- Date line(s): `Entrega 7 de octubre 2020`
- LaTeX footprint: 1 `.tex` file(s), 6 image asset(s), 0 bibliography file(s), 1 PDF asset(s).

**Content Explanation**
This document is actually a geochemistry lab-style bitacora rather than an exam copy. It appears to summarize experimental procedures and concepts around oxidation, redox analysis, qualitative versus quantitative carbon analysis, and the use of lab equipment such as a Bunsen burner and muffle furnace.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Fuentes:`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Resumen Articulo

- Folder: `geoquimica-organica/Resumen Articulo`
- Main document: `geoquimica-organica/Resumen Articulo/main.tex`
- Visible title: `Facultad de Ciencias. Geoquímica orgánica`
- Author line(s): `Arteaga Hernández Alejandro Iabin`
- Date line(s): `Entrega 9 de octubre 2020`
- LaTeX footprint: 1 `.tex` file(s), 6 image asset(s), 0 bibliography file(s), 1 PDF asset(s).

**Content Explanation**
This is a summary document for an organic geochemistry reading. It situates geoquímica orgánica as a field, connects it to geology and petroleum studies, and reads like a disciplinary overview intended to synthesize the main contribution of an assigned article.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

## inteligencia-artificial

The AI folder contains project reports with agent design, environment modeling, and implementation planning.

### IA Proyecto FInal

- Folder: `inteligencia-artificial/IA Proyecto FInal`
- Main document: `inteligencia-artificial/IA Proyecto FInal/main.tex`
- Visible title: no formal `\title{}` found; the document appears to use a custom cover/title block.
- LaTeX footprint: 1 `.tex` file(s), 5 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is the final AI project report for an agent that plays Snake using neural networks. The visible text covers the motivation for neural networks, the game environment, the project goal, the need for training data, network training, and testing, so it documents both the problem framing and the implementation plan.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### Inteligencia Artificial

- Folder: `inteligencia-artificial/Inteligencia Artificial`
- Main document: `inteligencia-artificial/Inteligencia Artificial/Proyecto01/Reporte01.tex`
- Visible title: no formal `\title{}` found; the document appears to use a custom cover/title block.
- LaTeX footprint: 1 `.tex` file(s), 3 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This project report designs an autonomous drone agent. It introduces major approaches to AI, describes the agent and its environment, defines the REAS model, and explains how the team planned to simulate and evaluate the design in Unity, followed by advantages, disadvantages, and conclusions.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Introducción`, `Sobre el agente`, `Objetivo`, `Definición de REAS`, `Diseño e implementación`, `Ventajas & Desventajas`, `Conclusiones`, `Referencias`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

## intro-programacion-y-logica

This group blends introductory programming, language theory, formal logic, and digital logic exercises.

### Practica 1.

- Folder: `intro-programacion-y-logica/Practica 1.`
- Main document: `intro-programacion-y-logica/Practica 1./sbc-template.tex`
- Visible title: `Práctica 1 - Lógica Computacional`
- Author line(s): `Arteaga Hernández Alejandro 313033414`
- LaTeX footprint: 1 `.tex` file(s), 2 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a computational logic assignment built around formal reasoning about functions on lists and strings. The document proves correctness properties, discusses partial functions, domains, injectivity, and recursive construction, so it reads as a proof-based logic exercise rather than a coding manual.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### Practica01_icc

- Folder: `intro-programacion-y-logica/Practica01_icc`
- Main document: `intro-programacion-y-logica/Practica01_icc/main.tex`
- Visible title: `Practica 1 / Introducción a las herramientas del laboratorio`
- Author line(s): `iabin Arteaga`
- Date line(s): `August 2019`
- LaTeX footprint: 1 `.tex` file(s), 1 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
Although the title suggests a lab-tools introduction, the body is really a Java basics worksheet. It explains primitive numeric types and strings, lists a set of methods the student must implement, and references an automated test suite, so it blends introductory programming practice with lab workflow.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### Tarea 4

- Folder: `intro-programacion-y-logica/Tarea 4`
- Main document: `intro-programacion-y-logica/Tarea 4/main.tex`
- Visible title: `Tarea 4`
- Author line(s): `iabin Arteaga`
- Date line(s): `November 2017`
- LaTeX footprint: 1 `.tex` file(s), 1 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a short programming-languages note about continuations and callbacks in Java. Its core example uses `CompletableFuture` to explain asynchronous chaining, showing how continuation-passing ideas surface in practical API design.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Introduction`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### Tarea lenguajes 1

- Folder: `intro-programacion-y-logica/Tarea lenguajes 1`
- Main document: `intro-programacion-y-logica/Tarea lenguajes 1/main.tex`
- Visible title: `Tarea 1`
- Author line(s): `Alejandro Iabin Arteaga Hernández`
- Date line(s): `Lenguajes de programación`
- LaTeX footprint: 1 `.tex` file(s), 1 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This assignment is a broad survey of programming languages. It compares languages by year, paradigm, creator, application domain, and distinctive features, and it ends with conceptual reflection on object orientation and language design tradeoffs.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### Tarea lenguajes 2

- Folder: `intro-programacion-y-logica/Tarea lenguajes 2`
- Main document: `intro-programacion-y-logica/Tarea lenguajes 2/main.tex`
- Visible title: `Tarea lenguajes 2`
- Author line(s): `Arteaga Hernández Alejandro Iabin`
- Date line(s): `Septiembre 2017`
- LaTeX footprint: 1 `.tex` file(s), 1 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This document continues the programming-languages theme with concrete language case studies, especially C# and PHP. It mixes code snippets with conceptual questions about evaluation, scope, binding, and language behavior, so it is partly descriptive and partly analytical.

**Structural Cues**
The section/chapter structure points to the following internal organization: `C#`, `Php`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### practica 01

- Folder: `intro-programacion-y-logica/practica 01`
- Main document: `intro-programacion-y-logica/practica 01/main.tex`
- Visible title: `Práctica 1 / Introducción a las herramientas del laboratorio`
- Date line(s): `Fecha limite de entrega 15 de agosto a las 23:59`
- LaTeX footprint: 1 `.tex` file(s), 1 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is an introductory lab handout and response sheet about basic tooling and course workflow. It focuses on repository setup, directory structure, class file organization, README expectations, compilation/execution steps, and the development process before writing larger programs.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Objetivo`, `Desarrollo`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### practica02

- Folder: `intro-programacion-y-logica/practica02`
- Main document: `intro-programacion-y-logica/practica02/main.tex`
- Visible title: `Práctica02`
- Author line(s): `Arteaga Hernández Alejandro Iabin / Barocio Gomez Luis Fernando / Olea Olvera Marco Ivan`
- LaTeX footprint: 1 `.tex` file(s), 0 image asset(s), 0 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a logic or digital design practice full of truth tables and Karnaugh maps. The exercises derive boolean expressions, minimize them, and analyze comparator/equality/direction logic, so the content is much closer to discrete logic design than general-purpose programming.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Ejercicios`.

**What To Expect If You Open It**
Expect a mostly text-only document with little reliance on figures.
The project does not appear to rely on a separate bibliography file; references, if any, are likely inline or omitted.

### tarea 3

- Folder: `intro-programacion-y-logica/tarea 3`
- Main document: `intro-programacion-y-logica/tarea 3/main.tex`
- Visible title: `tarea 3`
- Author line(s): `iabin Arteaga`
- Date line(s): `October 2017`
- LaTeX footprint: 1 `.tex` file(s), 1 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a theory-heavy programming-languages assignment. It contains proofs of equivalence between functions/programs, arguments about lazy versus eager evaluation, and a discussion of Turing completeness via mu-recursive functions and language expressiveness.

**Structural Cues**
The section/chapter structure points to the following internal organization: `4.1`, `4.2`, `4.3`, `Turing completez`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

## redes

The networking folder includes both infrastructure reports and more conceptual summaries and presentations.

### Documentación redes

- Folder: `redes/Documentación redes`
- Main document: `redes/Documentación redes/main.tex`
- Visible title: `Proyecto 1 de Redes de Computadoras`
- Author line(s): `Arteaga Hernández Alejandro Iabin\ / Barocio Gómez Luis Fernando\ / Olea Olvera Marco Iván`
- Date line(s): `Octubre 2019`
- LaTeX footprint: 1 `.tex` file(s), 14 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is the most operationally detailed networking document in the directory. It describes a full project deployment with a network diagram, DNS records, web/application/database/mail server configuration, application goals, testing instructions, and implementation commentary.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Diagrama de red`, `Registros DNS`, `Resúmenes de las configuraciones`, `Servidor web`, `Servidor de aplicación y base de datos`, `Servidor de correo electrónico`, `Esquema de la base de datos`, `Objetivo de la aplicación`, `Guión de pruebas para el uso de la aplicación`, `Comentarios`.

**What To Expect If You Open It**
Expect a visually dense document with many embedded diagrams or screenshots alongside the written explanation.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### Metropolis Beamer Theme

- Folder: `redes/Metropolis Beamer Theme`
- Main document: `redes/Metropolis Beamer Theme/demo.tex`
- Visible title: `Redes definidas por software`
- Author line(s): `Arteaga Hernández Alejandro`
- Date line(s): `today`
- LaTeX footprint: 1 `.tex` file(s), 1 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a slide deck version of the SDN topic rather than a generic theme demo. It presents a short talk on software-defined networking with an introduction, motivation, and closing slide, using Beamer/Metropolis as the presentation framework.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Introducción`, `¿Por qué surgen?`, `¡Gracias!`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### Redes definidas por software

- Folder: `redes/Redes definidas por software`
- Main document: `redes/Redes definidas por software/main.tex`
- Visible title: `Redes definidas por software SDN`
- Author line(s): `Arteaga Hernández Alejandro`
- Date line(s): `today`
- LaTeX footprint: 1 `.tex` file(s), 2 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a written report on software-defined networking. It contrasts SDN with traditional networks, explains why the model emerged, discusses benefits and importance, and closes with risks, disadvantages, and a concluding reflection.

**Structural Cues**
The section/chapter structure points to the following internal organization: `¿Cómo se diferencian con las redes tradicionales?`, `¿Qué son?`, `¿Por qué usar SDN?`, `¿Por qué son importantes?`, `Riesgos y desventajas`, `Conclusión`.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### RedesResumen

- Folder: `redes/RedesResumen`
- Main document: `redes/RedesResumen/main.tex`
- Visible title: `Una temprana historia de la Internet`
- Author line(s): `Arteaga Hernández Alejandro Iabin 313033414`
- Date line(s): `Septiembre 2018`
- LaTeX footprint: 1 `.tex` file(s), 2 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a historical summary of the early Internet. It traces the move toward packet switching, mentions Kleinrock and ARPANET, and reads like a concise history note for a networks course.

**Structural Cues**
This document has little or no explicit section structure in the main file, which usually means the content is either a compact answer sheet, a screenshot-heavy submission, or a cover-page-driven report.

**What To Expect If You Open It**
Expect a mostly text-based document with a small number of supporting figures or screenshots.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.

### redes2

- Folder: `redes/redes2`
- Main document: `redes/redes2/main.tex`
- Visible title: `Proyecto final:\ / Redes de computadoras`
- Author line(s): `Olea Olvera Marco\ / Barocio Gomez Luis Fernando\ / Arteaga Hernandez Alejandro`
- Date line(s): `Diciembre 2019`
- LaTeX footprint: 1 `.tex` file(s), 9 image asset(s), 1 bibliography file(s), 0 PDF asset(s).

**Content Explanation**
This is a final networking project report with a strong client-server flavor. It states the objective, explains the protocol design, gives instructions for running the system, and describes the application flow, ports, and local execution setup.

**Structural Cues**
The section/chapter structure points to the following internal organization: `Objetivo`, `Diseño del protocolo`, `Instrucciones de uso`, `Flujo del programa`.

**What To Expect If You Open It**
Expect a visually dense document with many embedded diagrams or screenshots alongside the written explanation.
A bibliography file is present, so the project likely cites readings, references, or web sources directly from BibTeX or a small companion bibliography.
