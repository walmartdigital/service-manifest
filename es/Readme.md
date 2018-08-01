# Manifiesto de Servicios

Buscamos representar la evolución de un servicio en un ambiente de constante cambio,
tomando en cuenta aspectos que consideramos importantes para fomentar un ambiente de
colaboración segura.

Buscamos representar el ciclo de vida de un servicio, para esto dividimos su estado en fases que describan su evolución de forma explícita, de modo que permita a terceros evaluar, implementar y colaborar conociendo de forma transparente el estado en que se encuentra.

---

## Fases

### Stage-0

Consideramos un servicio que ha sido desarrollado como **Prueba de Concepto** (**POC**, por sus siglas en inglés) que pretende resolver una idea y que puede ser desechado en cualquier momento bajo cualquier circunstancia.

### Stage-1

Consideramos un servicio que ha iniciado su desarrollo y que se encuentra en una etapa temprana
donde sus definiciones y caracteristicas pueden variar sin previo aviso y **sin considerar** explicitamente a terceros que interactúen con el.

Un servicio que se encuentre en esta etapa debe al menos contener:

- Un documento (**Readme**) que describa el dominio que pretende resolver y que explícitamente represente
  el estado en el que se encuentra.

### Stage-2

Consideramos un servicio que ha alcanzado una madurez en su dominio de negocio suficiente como para tener
bien definido gran parte de sus recursos. En esta etapa el servicio **considera a terceros** que se integren con el,
manteniendo los modelos externos inmutables ó retrocompatibilidad con los mismos y sólo ampliando el modelo de negocio.

Un servicio que se encuentre en esta etapa debe al menos contener:

- Cumpliri con Stage-1
- Documentación viva de sus recursos.
- Schema de interfaz definido (Restful, grpc, etc).

### Stage-3

Consideramos un servicio que ha alcanzado la madurez en su dominio de negocio y que ha sido abierta
a su comunidad para su mantenimiento y posible crecimiento.

Un servicio que se encuentre en esta etapa debe al menos contener:

- Debe cumplir con Stage-2
- Modelo de colaboración definido.

### Deprecated

Consideramos un servicio que va a ser desechado por los motivos que sea.

Un servicio que se encuentre en esta etapa debe al menos contener:

- Fecha de término del servicio de forma explícita.
