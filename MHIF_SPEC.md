# MHIF_SPEC.md

## Propósito

Este documento define la arquitectura técnica y conceptual del Meta Housing Intelligence Framework.

## Tipos de objetos

| Tipo | Prefijo | Uso |
|---|---|---|
| Rule | RULE | Regla de decisión |
| Signal | SIGNAL | Métrica o señal de análisis |
| Pattern | PATTERN | Patrón diagnóstico |
| Concept | CONCEPT | Concepto base |
| Framework | FRAMEWORK | Proceso de análisis |
| Playbook | PLAYBOOK | Procedimiento aplicable |
| Benchmark | BENCHMARK | Rango de referencia |
| Case | CASE | Caso real anonimizando |
| Prompt | PROMPT | Instrucción operativa |

## Pipeline obligatorio de análisis

INPUT  
→ Clasificar proyecto  
→ Clasificar etapa comercial  
→ Leer mercado  
→ Leer benchmarks  
→ Leer señales  
→ Detectar patrones  
→ Aplicar reglas  
→ Ejecutar framework  
→ Emitir hipótesis  
→ Calcular confianza  
→ Proponer acciones  
→ OUTPUT

## Principio rector

Toda métrica es un síntoma, nunca un diagnóstico.
