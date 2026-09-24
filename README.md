# PAFA — Perfil Argentino de Finanzas Abiertas

> Trabajo independiente · no oficial · ("WIP"- Work in progress)

El Decreto 353/2025 crea el Sistema de Finanzas Abiertas (SFA) y delega su reglamentación en el
BCRA. Lo que todavía no existe es la respuesta a una pregunta concreta: **¿cómo se ve, campo por
campo, el SFA argentino?** PAFA persigue ese fin, contestar con decisiones técnicas y sus contratos que las hacen implementables.

PAFA es una propuesta, no una norma ni un producto. No maneja datos reales y no tiene
vínculo con el BCRA ni con ninguna entidad gubernamental.

- **Por qué existe, qué propone y cómo avanza el proyecto → [pafa.ar](https://pafa.ar)**
- **La investigacion que acompña dicho perfil → [bezzone.me/research](https://bezzone.me/research)**
- **Algunas preguntas que todabia estan abiertas → [debates abiertos](https://github.com/users/EberB/projects/8)**

Este repositorio es el anexo técnico: las decisiones, los contratos y las preguntas abiertas, capa
por capa.

## Las cinco capas

| Capa | Pregunta que responde | Carpeta |
|---|---|---|
| **1 · Identidad y confianza entre participantes** | ¿quiénes son los participantes y cómo lo demuestran? | [`01-identidad-y-confianza/`](01-identidad-y-confianza/) |
| **2 · Autenticación, consentimiento y autorización** | ¿cómo autoriza el titular y cómo eso se vuelve un permiso técnico? | [`02-consentimiento-y-autorizacion/`](02-consentimiento-y-autorizacion/) |
| **3 · Recursos** | ¿qué datos se exponen y con qué contrato? | [`03-recursos/`](03-recursos/) |
| **4 · Observabilidad** | ¿cómo se sabe si el sistema funciona? | [`04-observabilidad/`](04-observabilidad/) |
| **5 · Gobernanza** | ¿quién entra, quién decide y quién responde? | [`05-gobernanza/`](05-gobernanza/) | 

La auditoría es transversal a todas las capas y será abordada en cada capa correspondiente.

## Desarrollo colaborativo: ¿Cómo participar?
La crítica concreta vale más que el acuerdo general: *"este campo está mal"*, *"este estado sobra"*,
*"esto no se puede implementar en un banco de verdad"*.

Se propone un tablero con discusiones abiertas para tener un espacio para debatir estos puntos.
[Debates abiertos](https://github.com/users/EberB/projects/8).


## Versiones

Cada cambio queda registrado en [`CHANGELOG.md`](CHANGELOG.md); los tags son `pafa-vX.Y.Z`.
## Licencia

[Apache License 2.0](LICENSE). 

---

Escrito por Eber Bezzone · Mas información en [bezzone.me/research](https://bezzone.me/research).
