# DECY — Public test tracker

`decy-testing` is the public issue tracker for the DECY test program.

The important change is simple: **testers are not expected to use GitHub to report problems.** Feedback is submitted from the DECY app. The DECY backend stores the private report and its allowed technical context, then creates or updates an anonymized issue here when it is useful for development.

---

## Français

### À quoi sert ce dépôt ?

Ce dépôt est une **projection publique des incidents et retours utiles au développement de DECY**.

Flux cible :

```text
DECY app
→ Signaler un problème
→ backend DECY
→ stockage privé + contexte technique autorisé
→ déduplication / regroupement
→ issue anonymisée dans decy-testing
```

Vous n’avez pas besoin d’un compte GitHub pour signaler un problème dans DECY et vous ne devez pas recopier manuellement les informations techniques de votre téléphone.

### Confidentialité

La base DECY reste la source de vérité du feedback. Ce dépôt public ne doit recevoir automatiquement que des informations techniques anonymisées utiles au développement : version de l’application, plateforme, écran ou fonctionnalité concernée, type d’erreur, occurrence et contexte technique borné.

Ne doivent jamais être publiés automatiquement ici : nom ou email, identifiant interne de compte/appareil, token ou secret, contenu d’un contrat ou document, audio ou transcription, montants personnels, noms d’objets/projets/engagements ou autres données privées DECY.

### Accès et fonctions distantes

DECY évolue vers un modèle compte/session pour les fonctions distantes. Les anciennes clés alpha ne constituent plus le modèle cible et ne sont pas distribuées via ce dépôt.

DECY reste conçu pour conserver localement les données personnelles et décisionnelles de l’utilisateur ; la connexion à un compte ne signifie pas une synchronisation automatique de ces données.

---

## English

### What is this repository for?

This repository is a **public projection of DECY incidents and feedback useful to development**.

Target flow:

```text
DECY app
→ Report a problem
→ DECY backend
→ private report + allowed technical context
→ deduplication / grouping
→ anonymized issue in decy-testing
```

Testers do not need a GitHub account to report a problem in DECY and are not expected to manually collect technical information from their device.

### Privacy

The private DECY backend remains the source of truth for feedback. This public repository should only receive anonymized technical information useful to development, such as app version, platform, affected screen/feature, error class, occurrence count and bounded technical context.

The following must never be published here automatically: name or email, internal account/device identifiers, tokens or secrets, contract/document contents, audio or transcripts, personal amounts, names of assets/projects/engagements, or other private DECY data.

### Access and remote features

DECY is moving to account/session based access for remote capabilities. Legacy alpha keys are no longer the target model and are not distributed through this repository.

DECY remains local-first for personal and decision data; signing into an account does not imply automatic synchronization of that data.

---

## Español

### ¿Para qué sirve este repositorio?

Este repositorio es una **proyección pública de incidencias y comentarios de DECY útiles para el desarrollo**.

Flujo objetivo:

```text
App DECY
→ Informar de un problema
→ backend DECY
→ informe privado + contexto técnico autorizado
→ deduplicación / agrupación
→ issue anonimizada en decy-testing
```

Los usuarios no necesitan una cuenta de GitHub para informar de un problema en DECY y no tienen que recopilar manualmente la información técnica del dispositivo.

### Privacidad

El backend privado de DECY sigue siendo la fuente de verdad de los informes. Este repositorio público solo debe recibir información técnica anonimizada útil para el desarrollo: versión de la aplicación, plataforma, pantalla o función afectada, tipo de error, número de ocurrencias y contexto técnico limitado.

Nunca deben publicarse automáticamente aquí: nombre o email, identificadores internos de cuenta/dispositivo, tokens o secretos, contenido de contratos o documentos, audio o transcripciones, importes personales, nombres de objetos/proyectos/compromisos ni otros datos privados de DECY.

### Acceso y funciones remotas

DECY evoluciona hacia un modelo de cuenta/sesión para las funciones remotas. Las antiguas claves alfa ya no son el modelo objetivo y no se distribuyen a través de este repositorio.

DECY sigue siendo local-first para los datos personales y de decisión; iniciar sesión no implica sincronizar automáticamente esos datos.

---

## APK de test / Test APK

When a test APK is published, use the repository **Releases** section. APK files should not be committed directly to the repository.

Lorsqu’un APK de test est publié, utilisez la section **Releases** du dépôt. Les APK ne doivent pas être commités directement dans le dépôt.

Cuando se publique un APK de prueba, utilice la sección **Releases** del repositorio. Los APK no deben añadirse directamente al repositorio.
