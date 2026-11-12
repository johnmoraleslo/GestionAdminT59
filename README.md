# 🏢 Torre 59 · Portal de copropietarios

Portal web para la administración financiera de una copropiedad de 36 apartamentos en Medellín. Reemplaza un control manual en Excel y permite que cada propietario consulte, desde el celular, el estado de cuenta de su apartamento de forma transparente.

## ¿Qué resuelve?
- **Propietarios:** ven cuánto han pagado, su saldo, el estado mes a mes y en qué se gasta el dinero de la torre.
- **Administrador:** registra pagos y gastos, ve la caja, la cartera pendiente y los honorarios por pagar.
- **Privacidad:** cada apartamento solo puede ver su propia información.

## Tecnologías
- HTML, CSS y JavaScript
- Supabase (PostgreSQL + Auth)
- Row Level Security (seguridad por filas) para aislar los datos por apartamento
- GitHub Pages para el despliegue

## Decisiones de diseño
- La deuda está ligada al **apartamento**, no a las personas, porque los residentes cambian.
- Interfaz de letra grande y alto contraste, pensada para adultos mayores.
- Los datos del Excel original se migraron a la base de datos sin pérdida de información.

## Autor
John Alejandro Morales López · [github.com/johnmoraleslo](https://github.com/johnmoraleslo)
