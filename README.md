# 🧾 FactumCore — Sistema de Facturación Web

**FactumCore** es el núcleo del sistema de facturación **Factum**, desarrollado como proyecto académico en la materia *Web Services*.

Este repositorio centraliza la documentación y la integración de los módulos:
- [ClienteRepository](https://github.com/Sistema-de-Facturacion-Factum/ClienteRepository)
- [ProductoRepository](https://github.com/Sistema-de-Facturacion-Factum/ProductoRepository)
- [FacturaRepository](https://github.com/Sistema-de-Facturacion-Factum/FacturaRepository)
- [UsuarioRepository](https://github.com/Sistema-de-Facturacion-Factum/UsuarioRepository)

---

## 🧩 Arquitectura del Sistema

┌──────────────────────┐
│ API (Controllers) │ → Endpoints REST
└─────────┬────────────┘
│
┌─────────▼────────────┐
│ Services Layer │ → Lógica de negocio
└─────────┬────────────┘
│
┌─────────▼────────────┐
│ Repository Layer │ → Acceso a datos (MySQL)
└─────────┬────────────┘
│
┌─────────▼────────────┐
│ Domain Models │ → Entidades: Cliente, Producto, Factura, Usuario
└──────────────────────┘

## 📁 Estructura del Repositorio

FactumCore/
├── src/
│ ├── controllers/
│ ├── services/
│ ├── models/
│ ├── repositories/
│ └── routes/
├── docs/
│ ├── Entregable1.pdf
│ ├── Parcial_WS.pdf
│ └── Alcance_Factum.md


---

## 👤 Autor

**Nicolás José Machado Martínez**  
Unidad Tecnológica de Santander — 2025
