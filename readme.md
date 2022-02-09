Demo of this project can be found [here](https://www.youtube.com/watch?v=aE1Cxbio5l8)

**Avance de la simulación de control de registros médicos para el curso de Algoritmos Avanzados**:

**Exposición**:

La atención de los pacientes en los centros de salud llega a ser demasiado lenta por el manejo de sus registros médicos, ya que en su mayoría son físicos, cada paciente debe de esperar que un personal de salud autorizado busque su historial o cree uno nuevo, para así ser atendido.

El modelo del sistema de registros de atención médica centralizado para el paciente controla el historial de registros anteriores y la actualización de los mismos. El paciente puede otorgar o revocar permisos mediante la identificación del médico. Todos los registros médicos estarán protegidos en la red blockchain y permanecerán a prueba de manipulaciones. El usuario configuraría transacciones específicas y detalladas sobre quién tiene acceso, la cantidad de tiempo asignado para el acceso y los tipos particulares de datos a los que se puede acceder.

**Dependencia del Sistema**:

    - mysql-server

**Dependencias usando npm**:
    
    - "body-parser": "^1.18.3",
    - "brfs": "^2.0.2",
    - "browserify": "^16.2.3",
    - "crypto": "^1.0.1",
    - "cryptr": "^4.0.2",
    - "express": "^4.16.4",
    - "mysql2": "^1.6.5",
    - "sequelize": "^5.2.13",
    - "solc": "^0.5.7",
    - "web3": "^1.0.0-beta.34"


**Las siguientes rutas son compatibles:**
    
    - Resgistrar pacientes desde 'localhost:3000/register'
    - Dar permiso a los médicos desde 'localhost:3000/patient'
    - Crear registro para un paciente desde 'localhost:3000/record'
    - Ver un registro de un paciente en particular desde 'localhost:3000/view'
    - Comparte un registro desde 'localhost:3000/share'



