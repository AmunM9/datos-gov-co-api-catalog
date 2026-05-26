# Datos Abiertos Colombia — Catálogo de APIs Públicas

Portal: https://www.datos.gov.co
Plataforma: Socrata (SODA API)
Patrón de consulta: `https://www.datos.gov.co/resource/{ID}.json`

**Resumen:** Un catálogo curado de las APIs y conjuntos de datos públicos de Colombia, organizados para facilitar su consumo y análisis.

La API se puede usar sin token para probar cualquier dataset público directamente desde el navegador o con curl. Para acceder a set de datos privados o que requieran mayor cantidad de consultas (no hay rate limit documentado), se recomienda tener un token.

App Token (opcional): registrarse en https://www.datos.gov.co/login, ir al perfil de developer y generar un App Token. Se envía como header `X-App-Token` o como parámetro `$$app_token` en la URL.

Esta es una selección de los datasets más destacados. Puedes consultar el catálogo completo directamente en el portal.

---

## Seguridad ciudadana y justicia

Fuente oficial: dataset estratégico `bbf6-qe46` publicado por MinTIC.

| ID | Título | Entidad | API | Requiere Login |
|----|--------|---------|-----|----------------|
| `3jdh-nmwu` | Reporte Capturas Policía Nacional | Policía Nacional | https://www.datos.gov.co/resource/3jdh-nmwu.json | No |
| `4rxi-8m8d` | Hurto Personas | Min. Defensa | https://www.datos.gov.co/resource/4rxi-8m8d.json | No |
| `4v6r-wu98` | Delitos Informáticos | Min. Defensa | https://www.datos.gov.co/resource/4v6r-wu98.json | No |
| `cmxv-8tb9` | Frentes de Seguridad Policía Nacional | Policía Nacional | https://www.datos.gov.co/resource/cmxv-8tb9.json | No |
| `npcj-hpw7` | Gestión de PQRS Minjusticia | Min. Justicia | https://www.datos.gov.co/resource/npcj-hpw7.json | No |
| `fuyf-sb4r` | Procesos en Casas de Justicia | Min. Justicia | https://www.datos.gov.co/resource/fuyf-sb4r.json | No |
| `yh8b-89bi` | Caracterización Personas en Casas de Justicia | Min. Justicia | https://www.datos.gov.co/resource/yh8b-89bi.json | No |
| `bmcc-69wd` | Directorio Casas de Justicia y Centros de Convivencia | Min. Justicia | https://www.datos.gov.co/resource/bmcc-69wd.json | No |
| `xm4c-2rks` | Solicitudes de Conciliación | Min. Justicia | https://www.datos.gov.co/resource/xm4c-2rks.json | No |
| `ii2p-naes` | Zonas y Distritos Militares Ejército Nacional | Ejército Nacional | https://www.datos.gov.co/resource/ii2p-naes.json | No |
| `iaeu-rcn6` | Antecedentes Disciplinarios SIRI | Procuraduría General | https://www.datos.gov.co/resource/iaeu-rcn6.json | No |
| `d4fr-sbn2` | Reporte Hurto por Modalidades Policía Nacional | Policía Nacional | https://www.datos.gov.co/resource/d4fr-sbn2.json | No |

---

## Salud y bienestar

| ID | Título | Entidad | API | Requiere Login |
|----|--------|---------|-----|----------------|
| `c36g-9fc2` | REPS – Prestadores y Sedes de Servicios de Salud | MinSalud | https://www.datos.gov.co/resource/c36g-9fc2.json | No |
| `n4dj-8r7k` | Clicsalud – Termómetro de Precios de Medicamentos | MinSalud | https://www.datos.gov.co/resource/n4dj-8r7k.json | No |
| `vw9t-pugy` | Clicsalud – Indicadores de Calidad EPS | MinSalud | https://www.datos.gov.co/resource/vw9t-pugy.json | No |
| `4e4i-ua65` | Indicadores Mortalidad y Morbilidad por municipio y año | MinSalud | https://www.datos.gov.co/resource/4e4i-ua65.json | No |
| `i5t3-2ui7` | Recursos del Sistema General – Giros | MinSalud | https://www.datos.gov.co/resource/i5t3-2ui7.json | No |
| `tq4m-hmg2` | Población BDUA Régimen Contributivo | ADRES | https://www.datos.gov.co/resource/tq4m-hmg2.json | No |
| `tmet-yeek` | Casos Positivos Viruela Símica | INS | https://www.datos.gov.co/resource/tmet-yeek.json | No |
| `dpcy-dq5j` | Embarazo en Adolescentes | Dir. Territorial Salud Caldas | https://www.datos.gov.co/resource/dpcy-dq5j.json | No |
| `gt2j-8ykr` | COVID-19 – Casos Confirmados Colombia (histórico) | INS | https://www.datos.gov.co/resource/gt2j-8ykr.json | No |
| `3he6-m866` | SISMED – Precios Medicamentos Canal Comercial | MinSalud | https://www.datos.gov.co/resource/3he6-m866.json | No |
| `3t73-n4q9` | SISMED – Precios Medicamentos Canal Institucional | MinSalud | https://www.datos.gov.co/resource/3t73-n4q9.json | No |

---

## Transporte y movilidad

| ID | Título | Entidad | API | Requiere Login |
|----|--------|---------|-----|----------------|
| `72nf-y4v3` | Historial de Multas SIMIT / FCM | Federación Col. Municipios | https://www.datos.gov.co/resource/72nf-y4v3.json | No |
| `rs3u-8r4q` | Sectores Críticos de Siniestralidad Vial | ANSV | https://www.datos.gov.co/resource/rs3u-8r4q.json | No |
| `fr9f-9g4b` | Encuesta Motociclistas | ANSV | https://www.datos.gov.co/resource/fr9f-9g4b.json | No |
| `cm2t-qreq` | Encuesta Territorial Comportamiento Seguridad Vial | ANSV | https://www.datos.gov.co/resource/cm2t-qreq.json | No |
| `24ny-2dhf` | Sectores Críticos por Exceso de Velocidad | ANSV | https://www.datos.gov.co/resource/24ny-2dhf.json | No |
| `2h8t-2zik` | Información Pasajeros Transporte Masivo | Min. Transportes | https://www.datos.gov.co/resource/2h8t-2zik.json | No |
| `u3vn-bdcy` | Crecimiento Parque Automotor RUNT 2.0 | Min. Transportes | https://www.datos.gov.co/resource/u3vn-bdcy.json | No |
| `tfrd-amb4` | Tiempos Logísticos Vehículos de Carga | Min. Transportes | https://www.datos.gov.co/resource/tfrd-amb4.json | No |
| `eh75-8ah6` | Operación Pasajeros y Despacho por Carretera | Supertransporte | https://www.datos.gov.co/resource/eh75-8ah6.json | No |
| `7atu-2b28` | Tráfico Pasajeros y Carga Férreo | Supertransporte | https://www.datos.gov.co/resource/7atu-2b28.json | No |
| `5r3g-zv5z` | Tráfico Portuario Marítimo | Supertransporte | https://www.datos.gov.co/resource/5r3g-zv5z.json | No |

---

## Gastos gubernamentales y contratación pública

| ID | Título | Entidad | API | Requiere Login |
|----|--------|---------|-----|----------------|
| `jbjy-vk9h` | SECOP II – Contratos Electrónicos | Colombia Compra Eficiente | https://www.datos.gov.co/resource/jbjy-vk9h.json | No |
| `p6dx-8zbt` | SECOP II – Procesos de Contratación | Colombia Compra Eficiente | https://www.datos.gov.co/resource/p6dx-8zbt.json | No |
| `rpmr-utcd` | SECOP Integrado (I + II) | Colombia Compra Eficiente | https://www.datos.gov.co/resource/rpmr-utcd.json | No |
| `qmzu-gj57` | SECOP II – Proveedores Registrados | Colombia Compra Eficiente | https://www.datos.gov.co/resource/qmzu-gj57.json | No |
| `rgxm-mmea` | Tienda Virtual del Estado Colombiano – Consolidado | Colombia Compra Eficiente | https://www.datos.gov.co/resource/rgxm-mmea.json | No |

---

## Agricultura y desarrollo rural

| ID | Título | Entidad | API | Requiere Login |
|----|--------|---------|-----|----------------|
| `5fct-ib9u` | Exportaciones Agrícolas No Tradicionales y Tradicionales | Min. Agricultura | https://www.datos.gov.co/resource/5fct-ib9u.json | No |
| `3usu-fpk5` | Productores con Acuerdos Comerciales – Agricultura por Contrato | Min. Agricultura | https://www.datos.gov.co/resource/3usu-fpk5.json | No |
| `h3uz-jvkj` | Área Plantada con Plantaciones Forestales Comerciales | Min. Agricultura | https://www.datos.gov.co/resource/h3uz-jvkj.json | No |
| `rttb-pk7n` | Precios Comerciales Tierra Rural Agropecuaria | Min. Agricultura | https://www.datos.gov.co/resource/rttb-pk7n.json | No |
| `gwbi-fnzs` | Índice de Precios de Insumos Agrícolas | UPRA | https://www.datos.gov.co/resource/gwbi-fnzs.json | No |
| `fptv-axay` | Madera Movilizada Plantaciones Forestales | Min. Agricultura | https://www.datos.gov.co/resource/fptv-axay.json | No |
| `eenu-gmwi` | Registro Activos de Información Min. Agricultura | Min. Agricultura | https://www.datos.gov.co/resource/eenu-gmwi.json | No |

---

## Urbanismo y planificación territorial

| ID | Título | Entidad | API | Requiere Login |
|----|--------|---------|-----|----------------|
| `hurd-27bj` | Predios Titulados a Nivel Nacional | Min. Vivienda | https://www.datos.gov.co/resource/hurd-27bj.json | No |
| `h2yr-zfb2` | Subsidios de Vivienda Asignados | Min. Vivienda | https://www.datos.gov.co/resource/h2yr-zfb2.json | No |
| `yt5q-ekus` | Focalización Políticas Transversales | DNP | https://www.datos.gov.co/resource/yt5q-ekus.json | No |
| `uds4-jdij` | Plan de Desarrollo | DNP | https://www.datos.gov.co/resource/uds4-jdij.json | No |
| `nkjx-rsq7` | Medición del Desempeño Municipal | DNP | https://www.datos.gov.co/resource/nkjx-rsq7.json | No |
| `u3qu-swda` | Ejecución Proyecto por DIVIPOLA | DNP | https://www.datos.gov.co/resource/u3qu-swda.json | No |

---

## Geografía y referencias

| ID | Título | Entidad | API | Requiere Login |
|----|--------|---------|-----|----------------|
| `ixig-z8b5` | Códigos Postales Nacionales | 4-72 | https://www.datos.gov.co/resource/ixig-z8b5.json | No |

---

## Educación

Los resultados del ICFES Saber 11 están fragmentados por semestre. No existe un dataset único consolidado en datos.gov.co.

| ID | Título | Entidad | API | Requiere Login |
|----|--------|---------|-----|----------------|
| `ynam-yc42` | Saber 11 – 2019-2 | ICFES | https://www.datos.gov.co/resource/ynam-yc42.json | Sí |
| `a8xr-en99` | Saber 11 – 2020-1 | ICFES | https://www.datos.gov.co/resource/a8xr-en99.json | No |
| `ptck-fi3s` | Saber 11 – 2018-1 Refinado | ICFES | https://www.datos.gov.co/resource/ptck-fi3s.json | Sí |
| `72fv-ej37` | Matriculados por Nacionalidad | Universidad del Quindío | https://www.datos.gov.co/resource/72fv-ej37.json | No |

---

## Índice maestro

| ID | Título | API | Requiere Login |
|----|--------|-----|----------------|
| `bbf6-qe46` | Conjuntos de Datos Estratégicos Nacionales (índice con URLs) | https://www.datos.gov.co/resource/bbf6-qe46.json | Sí |

---

## Cómo consumir la API

### JavaScript (fetch)

```javascript
// Token opcional — si lo tienes, agrégalo como header
const headers = {};
// headers["X-App-Token"] = "TU_APP_TOKEN";

const response = await fetch(
  "https://www.datos.gov.co/resource/72nf-y4v3.json?placa=ABC123&$limit=10",
  { headers }
);
const data = await response.json();
console.log(data);
```

### JavaScript (consulta avanzada con SoQL)

```javascript
const headers = { "Content-Type": "application/json" };
// headers["X-App-Token"] = "TU_APP_TOKEN"; // opcional

fetch("https://www.datos.gov.co/api/v3/views/rs3u-8r4q/query.json", {
  method: "POST",
  headers,
  body: JSON.stringify({
    query: "SELECT * WHERE departamento = 'Cundinamarca'",
    page: { pageNumber: 1, pageSize: 5000 },
    includeSynthetic: false
  })
})
  .then(res => res.json())
  .then(data => console.log(data));
```

### Python (sodapy + pandas)

```python
import pandas as pd
from sodapy import Socrata

# Sin token (funciona, pero con throttle por IP)
client = Socrata("www.datos.gov.co", None)

# Con token (opcional, recomendado para uso frecuente)
# client = Socrata("www.datos.gov.co", "TU_APP_TOKEN")

results = client.get("72nf-y4v3", where="placa='ABC123'", limit=2000)
df = pd.DataFrame.from_records(results)
print(df)
```

### cURL

```bash
# Sin token
curl "https://www.datos.gov.co/resource/jbjy-vk9h.json?\$limit=5"

# Con token (opcional)
curl -H "X-App-Token: TU_APP_TOKEN" \
  "https://www.datos.gov.co/resource/jbjy-vk9h.json?\$limit=5&\$where=valor_del_contrato>1000000000"
```

---

## Consideraciones

**Ver detalles de un dataset:** Para acceder a la página con la información y ficha técnica de un dataset, simplemente elimínale la extensión `.json` a la URL. Por ejemplo: `https://www.datos.gov.co/resource/jbjy-vk9h.json` se convierte en `https://www.datos.gov.co/resource/jbjy-vk9h`.

**Cómo encontrar IDs reales:** El dataset `bbf6-qe46` es el índice oficial de datos estratégicos publicado por MinTIC. Tiene columnas `tematica`, `nombre_base`, `entidad` y `enlace`. El ID siempre es la última parte de la URL (ej: en `https://www.datos.gov.co/d/4rxi-8m8d` el ID es `4rxi-8m8d`). Alternativamente, buscar en Google con `site:datos.gov.co "nombre del dataset"`.

**Formatos de respuesta:** Cambiar `.json` por `.csv` o `.geojson` en el endpoint para obtener otros formatos. Ejemplo: `https://www.datos.gov.co/resource/72nf-y4v3.csv`.

**Límite por defecto:** Sin `$limit`, la API devuelve solo 1000 filas. Siempre especificar `$limit`. Para datasets grandes, paginar con `$limit` + `$offset`.

**SoQL (Socrata Query Language):** Soporta `$select`, `$where`, `$order`, `$group`, `$limit`, `$offset`, `$q` (búsqueda full-text). Sintaxis similar a SQL. Documentación completa: https://dev.socrata.com/docs/queries/

**Datasets que ya no existen:** Algunos IDs históricos devuelven `{"code":"dataset.missing"}`. Esto pasa cuando la entidad elimina o migra el dataset. No hay forma de prevenirlo, verificar antes de construir sobre un dataset.

**Fuentes complementarias fuera de datos.gov.co:**
- DANE Microdatos (censos y encuestas): https://microdatos.dane.gov.co
- DANE SIPSA (precios alimentos, Web Service SOAP): http://appweb.dane.gov.co/sipsaWS/SrvSipsaUpraBeanService?wsdl
- Banco de la República (tasas, inflación): https://www.banrep.gov.co/es/estadisticas
- AGRONET (producción agrícola): https://www.agronet.gov.co