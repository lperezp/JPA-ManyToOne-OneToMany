# JPA-ManyToOne-OneToMany

@OneToMany(mappedBy="personaContacto", cascade=CascadeType.ALL)
=>

@JsonManagedReference
@JsonBackReference
=> Sirve para no crear un bucle infinito. Para indicar quien es el padre e hijo.

@JoinColumn(name="nombre")
=> Sirve para dar el nombre a la columna de la llave primaria.
