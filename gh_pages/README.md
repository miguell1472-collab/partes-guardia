# 🏥 Partes de Guardia v12

**Sistema digital de partes de guardia hospitalaria** · Ecuador · Para médicos en guardia

[![Deploy](https://github.com/TU_USUARIO/partes-guardia/actions/workflows/deploy.yml/badge.svg)](https://github.com/TU_USUARIO/partes-guardia/actions)
[![PWA](https://img.shields.io/badge/PWA-Instalable-blue)](https://TU_USUARIO.github.io/partes-guardia)

---

## 🌐 Acceso directo

**URL:** `https://TU_USUARIO.github.io/partes-guardia`

Funciona en cualquier dispositivo: **iPhone · iPad · Android · PC · Mac**

---

## ✨ Funcionalidades principales

| Módulo | Descripción |
|--------|-------------|
| 📋 **SOAP por paciente** | 60 plantillas clínicas por especialidad |
| 💊 **Farmacología avanzada** | 200+ fármacos + protocolos con dosis ponderales |
| 💧 **Manejo de líquidos** | Holliday-Segar, Parkland, sepsis SSC 2021, hemoderivados |
| 💉 **Vasopresores** | Calculadora de infusión NE/Dopa/Dobut/Vaso con concentración estándar |
| 🦠 **ATB IV** | Protocolos empíricos sepsis/NAC/meningitis/ITU/abdomen con dosis ponderales |
| 🩸 **Insulina** | CAD/EHHNC/hiperglucemia hospitalaria paso a paso (ADA 2023) |
| 😴 **Analgosedación** | PAD Bundle, RASS, CPOT, escalas y fármacos UCI |
| 🫁 **RSI** | Intubación secuencia rápida con dosis calculadas y selección TET |
| ⚡ **Electrolitos** | Corrección hipoNa, hipoK, hiperK con calculadoras |
| 🔢 **CIE-10** | 700+ códigos con autocompletado en campo diagnóstico |
| 🧮 **Calculadoras** | HEART, Framingham, CHA₂DS₂-VASc, Padua, Wells TEP/TVP, qSOFA |
| ⏱ **Timer RCP** | Temporizador con ciclos, dosis adrenalina, bitácora |
| 📈 **Curvas OMS** | Peso/talla 0-60 meses con percentiles y punto del paciente |
| 🧠 **Denver II** | Escala de neurodesarrollo con registro pass/fail |
| 🤖 **IA por paciente** | Chat con Claude que conoce todos los datos del paciente |
| 📄 **Documentos** | Receta MSP, Epicrisis, Hoja de enfermería imprimibles |
| 🖨️ **Parte imprimible** | Documento formateado profesional con SOAP, vitales, firmas |
| 🔄 **Sincronización** | Exportar/importar con PIN, QR de resumen |
| 📊 **Estadísticas** | Dx frecuentes, distribución por especialidad |
| 🌙 **Modo nocturno** | Para las 3 AM en guardia |

---

## 📱 Instalación como app (sin App Store)

### iPhone / iPad (Safari)
1. Abre `https://TU_USUARIO.github.io/partes-guardia` en Safari
2. Toca el botón **Compartir** (□↑)
3. Selecciona **"Añadir a pantalla de inicio"**
4. Nombre: `Partes Guardia` → **Añadir**

### Android (Chrome)
1. Abre la URL en Chrome
2. Toca los **tres puntos** (⋮)
3. Selecciona **"Añadir a pantalla de inicio"**

### PC/Mac (Chrome/Edge)
1. En la barra de dirección aparecerá un icono de instalación
2. Clic en **"Instalar"**

---

## 🔒 Privacidad y seguridad

- **Sin servidor backend** — todos los datos se quedan en tu dispositivo
- Almacenamiento en **IndexedDB** local (sin límite de 5MB)
- Exportación con **PIN de encriptación** opcional
- Sin telemetría ni seguimiento
- Cumple con principios de datos mínimos (solo lo que tú introduces)

> ⚠️ No ingresar datos que permitan identificar pacientes reales sin anonimización (nombre completo + HC + DX). Para uso clínico con datos reales, consultar con tu institución sobre políticas de datos de salud.

---

## 🛠️ Cómo publicar tu propia copia

1. **Fork** este repositorio en GitHub
2. Ve a **Settings → Pages**
3. Source: **GitHub Actions**
4. Haz push de cualquier cambio para activar el deploy
5. Tu URL será: `https://TU_USUARIO.github.io/partes-guardia`

---

## 📚 Guías clínicas referenciadas

- SSC 2021 (Surviving Sepsis Campaign)
- AHA/ACLS 2020 · PALS 2020
- ADA Standards of Medical Care 2023
- IDSA Guidelines (Meningitis, NAC, ITU, Abdominales)
- ATLS 10ª Edición
- WHO Diarrhoea Treatment Manual
- ACOG Practice Bulletins 2021-2022
- SCCM PAD Bundle 2018
- ACCP/ASH Anticoagulation Guidelines 2021
- WAO Anaphylaxis Guidelines 2020
- Surviving Sepsis Campaign Pediatric 2020

---

## 💻 Tecnología

- HTML5 + CSS3 + JavaScript vanilla (sin frameworks)
- IndexedDB para almacenamiento persistente
- Service Worker para funcionalidad offline
- Progressive Web App (PWA) instalable
- Compatible con todos los navegadores modernos

---

*Desarrollado para médicos en año de salud rural · Ecuador · 2026*
