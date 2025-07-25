# qm cloudinit

> Configuración de ajustes de cloudinit para máquinas virtuales gestionadas por Ambiente Virtual Proxmox (Virtual Environment) (PVE).
> Más información: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Configura ajustes de cloudinit para un usuario específico y establece una contraseña para el mismo:

`qm cloudinit {{id_mv}} -user={{usuario}} -password={{contraseña}}`

- Configura ajustes de cloudinit para un usuario específico y le establece una contraseña con una clave SSH específica:

`qm cloudinit {{id_mv}} -user={{usuario}} -password={{contraseña}} -sshkey={{clave_ssh}}`

- Establece el nombre de host para una máquina virtual específica:

`qm cloudinit {{id_mv}} -hostname={{nombre_del_equipo}}`

- Configura los ajustes de interfaz de red para una máquina virtual específica:

`qm cloudinit {{id_mv}} -ipconfig {{ipconfig}}`

- Configura un script de interfaz de comandos (shell) para ejecutarse antes de que `cloudinit` se ejecute en una máquina virtual:

`qm cloudinit {{id_mv}} -pre {{script}}`
