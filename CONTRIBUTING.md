# Guía de Contribución · Contributing Guide

¡Gracias por tu interés en contribuir a un proyecto de **NeoNexAI**! 🙌
_Thanks for your interest in contributing to a **NeoNexAI** project!_

Esta guía aplica por defecto a todos los repositorios de la organización [`@neonexai`](https://github.com/neonexai) que no tengan su propia versión.

---

## 🇪🇸 Cómo contribuir

### 1. Antes de empezar

- Revisa los [issues abiertos](https://github.com/neonexai) por si tu idea ya está en marcha.
- Para cambios grandes, **abre primero un issue** para discutir el enfoque. Evita trabajo en vano.
- Lee nuestro [Código de Conducta](CODE_OF_CONDUCT.md).

### 2. Flujo de trabajo

1. Haz **fork** del repositorio y clónalo localmente.
2. Crea una rama descriptiva desde `main`:

   ```bash
   git checkout -b feat/mi-mejora      # o fix/, docs/, chore/, refactor/
   ```

3. Realiza tus cambios siguiendo el estilo del proyecto.
4. Asegúrate de que **pasa el linter y los tests** antes de hacer commit.
5. Haz commits claros siguiendo [Conventional Commits](https://www.conventionalcommits.org/):

   ```text
   feat: añade exportación a CSV
   fix: corrige cálculo del stop ATR
   docs: actualiza el README de instalación
   ```

6. Abre un **Pull Request** contra `main` rellenando la plantilla.

### 3. Nuestros principios de código (Karpathy principles)

1. **Think before coding** — entiende el problema antes de teclear.
2. **Simplicity** — la solución más simple que funcione gana.
3. **Surgical changes** — cambios mínimos y enfocados; no refactors masivos sin pedirlos.
4. **Goal-driven** — cada cambio responde a un objetivo concreto.
5. **Sin lock-in** — código portable, sin dependencias innecesarias.

### 4. Estándares de calidad

- **Tests**: si añades lógica, añade tests. Si arreglas un bug, añade un test de regresión.
- **Documentación**: actualiza el README o los docs si cambias comportamiento.
- **Sin secretos**: nunca subas claves, tokens ni `.env`. Usa variables de entorno.
- **Privacidad/RGPD**: cuidado con datos personales; cumplimos el RGPD.

---

## 🇬🇧 How to contribute (summary)

1. Open an issue first for large changes.
2. Fork → branch from `main` (`feat/`, `fix/`, `docs/`…).
3. Follow the existing code style; keep changes surgical.
4. Make sure linters and tests pass.
5. Use [Conventional Commits](https://www.conventionalcommits.org/).
6. Open a PR against `main` and fill in the template.

**Quality bar:** add tests for new logic and regression tests for bug fixes, update docs, never commit secrets or personal data (GDPR).

---

## 💬 ¿Dudas? · Questions?

- Soporte general: ver [SUPPORT.md](SUPPORT.md)
- Vulnerabilidades de seguridad: ver [SECURITY.md](SECURITY.md) (**no** abras un issue público)
- Contacto: [info@neonexai.com](mailto:info@neonexai.com)

---

_© 2026 NeoNexAI Agency_
