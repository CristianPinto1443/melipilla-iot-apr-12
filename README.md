# melipilla-iot-apr-12


# 🌱 Proyecto: Sistema de Monitoreo y Control de Riego con IoT  

En la agricultura, los invernaderos permiten mejorar la producción al proteger los cultivos de factores externos.  
Sin embargo, muchos pequeños agricultores aún riegan de forma manual y sin un control exacto del consumo de agua, lo que genera desperdicio.  

Este proyecto busca implementar un **sistema de riego inteligente en maqueta**, utilizando **IoT y Raspberry Pi**, capaz de medir el flujo de agua y activar el riego de manera programada y automática.  

---

## 🎯 Objetivo General  
Diseñar y prototipar un sistema de riego inteligente de bajo costo que registre el flujo de agua y lo active automáticamente en horarios específicos, optimizando el uso del recurso hídrico.  

---

## 👨‍💻 Integrantes  
- Cristian Pinto  
- Claudia Campos  
- Dixie Marín  

---

## 🔧 Dispositivos y materiales  

### Controlador principal  
- Raspberry Pi (cualquier modelo con GPIO).  
- Fuente de poder y memoria microSD.  

### Sensores  
- Sensor de flujo de agua (para medir cuántos litros pasan por la manguera).  

### Actuadores  
- Módulo de relé (para controlar una bomba o válvula de agua).  
- Bomba de agua pequeña o válvula eléctrica (para simular el riego).  

### Estructura  
- Maqueta de invernadero o sistema de riego con mangueras.  
- Protoboard y cables de conexión.  

### Visualización y control  
- Software en Raspberry Pi (ejemplo: Node-RED o Python).  
- Dashboard web sencillo para ver el consumo de agua y programar riego.  

---

## ⚡ Diagrama funcional básico  
1. El **sensor de flujo** mide cuánta agua pasa → envía datos a la **Raspberry Pi**.  
2. La **Raspberry Pi** procesa la información y decide cuándo activar la bomba/válvula.  
3. El sistema puede activarse automáticamente en un horario definido o manualmente desde el **dashboard web**.  

---

## 💡 Ejemplo de uso en maqueta  
- El sistema **se activa a las 10:00 AM** y abre el paso del agua durante 2 minutos.  
- Mientras funciona, el **sensor de flujo** mide el consumo exacto (ejemplo: *1,5 litros*).  
- El agricultor puede revisar en su celular cuánto agua se usó y llevar un registro histórico.  

---

