# Reto-4
# 📊 Análisis sobre el impacto de los días festivos y las categorías en las ventas

Para este análisis utilicé un dataset con todas las ventas de un año, donde además están identificados los días festivos.  
El objetivo fue entender si realmente esos días marcan una diferencia frente a los días normales y, a partir de ahí, profundizar en la estacionalidad mensual y en qué categorías fueron las que más impulsaron las ventas.  

---

## 1. Días festivos vs no festivos  

Lo primero que hice fue comparar las ventas en promedio por día festivo frente a los no festivos.  

- En los días no festivos, obviamente el volumen total es mucho mayor porque son casi todo el año.  
- Pero lo que me interesaba era la **venta promedio por día**, y ahí sí se ve un hallazgo clave:  

| Tipo de día   | Promedio por día |
|---------------|-----------------|
| Festivos      | **409**         |
| No festivos   | **303**         |

Esto significa que en los festivos se vende alrededor de un **35% más por día**.  

➡️ Esto me lleva a pensar que en esos días los clientes optan por comprar productos de mayor valor o en mayor cantidad, lo cual confirma que los festivos son oportunidades importantes de venta.  

---

## 2. Evolución mensual de las ventas  

Después miré la estacionalidad: cómo se comportaron las ventas a lo largo del año.  

- 📈 Febrero: crecimiento de **+11%**.  
- 📉 Marzo a mayo: tres meses seguidos de caída.  
- ❓ Junio, agosto y noviembre: **cero ventas** (posible error en los datos o meses sin operación).  
- 📈 Julio: repunte fuerte.  
- 📈 Octubre: crecimiento importante.  
- 🎯 Diciembre: mes más fuerte, con un crecimiento de **+167%** respecto al mes anterior.  

➡️ Con esto se ve claro que **febrero, julio, octubre y diciembre** son meses claves para planificar campañas o reforzar inventario.  

---

## 3. Categorías que impulsaron las ventas  

Para responder qué categorías fueron las que más pesaron, armé tablas dinámicas mostrando la participación mensual (%) y también el crecimiento mes a mes.  

### Hallazgos por categoría  

- 🥩 **Carnes**: muy consistentes, en al menos 5 meses tuvieron más del 20% de participación. Categoría **estructural del negocio**.  
- 🥖 **Panadería**: fuerte en mayo (32%) y en diciembre (22%), meses donde destacó con fuerza.  
- 🍫 **Snacks**: representativos en enero, abril y julio, con un pico de +171% en julio. Funcionan bien en ciertos momentos, pero no son constantes.  
- 🥤 **Bebidas**: en marzo llegaron al 31%, pero después cayeron hasta julio. Desde el segundo semestre crecieron de manera sostenida, aunque sin llegar a ser la categoría más fuerte.  
- 🥛 **Lácteos**: en general tuvieron poca representación, pero en diciembre explotaron (+230%) y alcanzaron el 20% de las ventas.  

### Resumen  
- **Carnes** → categoría estable todo el año.  
- **Panadería y Lácteos** → categorías estacionales (picos fuertes en ciertas fechas).  
- **Bebidas y Snacks** → categorías de impulso, más dependientes de contexto o campañas.  

---

## 4. Recomendaciones accionables  

1. **Planificación de inventario en festivos**  
   - Si en promedio se vende **35% más en festivos**, conviene anticipar stock y priorizar categorías que suelen crecer en esas fechas.  

2. **Campañas en meses clave**  
   - Febrero, julio, octubre y diciembre deberían tener **promociones especiales**, ya que concentran la mayor parte del crecimiento.  

3. **Gestión de categorías**  
   - 🥩 Carnes: mantener abastecimiento estable.  
   - 🥖 Panadería y 🥛 Lácteos: enfocarlos en campañas estacionales (ejemplo: diciembre).  
   - 🥤 Bebidas y 🍫 Snacks: impulsar combos o promociones para aumentar su ticket promedio.  

4. **Revisión de datos**  
   - Validar los meses en blanco (**junio, agosto, noviembre**) para determinar si son errores de registro o periodos sin operación.  

---

## 📌 Conclusión  

- Los **festivos sí tienen un impacto positivo** en las ventas diarias (+35%).  
- Los meses de mayor fuerza son **febrero, julio, octubre y diciembre**.  
- Las categorías muestran un comportamiento mixto:  
  - Estables: 🥩 Carnes.  
  - Estacionales: 🥖 Panadería, 🥛 Lácteos.  
  - De impulso: 🥤 Bebidas, 🍫 Snacks.  

Esto da una base sólida para **planificar inventario, promociones y estrategias de precios**.  
