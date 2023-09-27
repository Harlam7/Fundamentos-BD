# Fundamentos-BD
![ae6e9906853414a0dedddfe7a6dfd716](https://github.com/Harlam7/Fundamentos-BD/assets/31184547/3537e2b8-495f-48f8-b342-654bdd3b533d)
![4zjxm](https://github.com/Harlam7/Fundamentos-BD/assets/31184547/c2d6efa8-7d54-4fa9-a24b-813f50bb0c74)

https://www.goconqr.com/mindmap/22606096/fundamentos-de-bases-de-datos

Quiero obtener todos los post creados por_

SELECT: Lo que quieres mostrar
Nickname
Titulo del post
FROM: De dónde voy a tomar los datos
Tabla usuarios y post
WHERE: Los filtros de los datos que quieres mostrar
Deben de ser de edgar@com
GROUP BY: Los rubros por los que me interesa agrupar la información
No deseo agrupar
ORDER BY: El orden en que quiero presentar mi información
por fecha de publicación
HAVING: Los filtros que quiero que mis datos agrupados tengan

SELECT u.nickname, p.titulo FROM usuarios u inner join posts p ON u.id=p.usuario_id where u.email="edgar@com" ORDER BY p.fecha_publicacion;
