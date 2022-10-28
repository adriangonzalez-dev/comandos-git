# Comandos con Git
(Para cancelar cualquier comando presionar la tecla Q )

## *Verificar versión de git instalada*
`git --version`
#### forma abreviada
`git -v`

------------
## *Listar los comandos soportados*
`git help`

#### Se puede acceder a la descripción de cada comando, por ej:
`git help commit`

------------

## *Configuración del usuario y correo*
`git config --global user.name "adrian gonzalez" user.email "adri@mail.com"`

#### El atributo --global configura el usuario para todos los proyectos que se inicien en el dispositivo. Solo retorna un mensaje en caso de error.

#### Para verificar si se guardo con exito:
`git config --global -e`

------------

## *Renombar rama master por main*
`git config --global init.defaultBranch <name>`

