

Guía para Contribuir (Contributing Guide)
¡Gracias por tu interés en contribuir a este proyecto de Computación Cuántica! Toda ayuda es bienvenida para hacer de este un recurso educativo excepcional.

Cómo empezar
Haz un Fork del repositorio.

Clona tu fork en tu máquina local:
git clone https://github.com/TU_USUARIO/Quantum-Computing.git

Crea una rama (branch) para tu contribución:
git checkout -b mejora-algoritmo-x

Reglas de Contribución
1. Estándares de Código
Si subes Jupyter Notebooks, asegúrate de que las celdas estén ejecutadas y los gráficos (como circuitos o esferas de Bloch) sean visibles.

Usa comentarios claros en Python para explicar los pasos del algoritmo.

Mantén la compatibilidad con Qiskit 0.23.0 (o especifica si usas una versión superior).

2. Documentación
Si añades un nuevo algoritmo, por favor incluye una pequeña explicación teórica o un enlace a la documentación oficial de IBM Quantum.

Usa LaTeX para las fórmulas matemáticas en los archivos Markdown o Notebooks. Por ejemplo:
|ψ⟩ = (1/√2) * (|0⟩ + |1⟩)

3. Reporte de Errores (Issues)
Si encuentras un error en el código o un concepto mal explicado:

Abre un Issue en GitHub.

Describe el problema detalladamente.

Si es posible, adjunta una captura de pantalla del error.

Código de Conducta
Al participar en este proyecto, te comprometes a seguir el Código de Conducta de Qiskit:

Ser respetuoso y profesional con los demás colaboradores.

Fomentar un entorno inclusivo para personas de todos los niveles.

Aceptar críticas constructivas para mejorar la calidad del material educativo.

Pruebas de Sistemas Fermiónicos
Si vas a contribuir al módulo de sistemas fermiónicos:

Recuerda que el núcleo está en Rust. Si modificas el núcleo, asegúrate de que los enlaces de Python sigan funcionando correctamente.

Verifica que las nuevas estructuras de datos sigan la filosofía de diseño de Qiskit.






































