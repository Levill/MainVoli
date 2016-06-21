# MainVoli

MOSTRAR
select servicios.nombre,unidades.nombre,reponsables.nombre,
tareas.nombre,tareas.fecha
from servicios,unidades,tareas,responsables
where
unidades.servicio_id=servicios.servicio_id and
responsables.unidad_id=unidades.unidad_id and tareas.responsable
