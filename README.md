# JPA-ManyToOne-OneToMany

@JsonManagedReference
@JsonBackReference
=> Sirve para no crear un bucle infinito. Para indicar quien es el padre e hijo.

@JoinColumn(name="nombre")
=> Sirve para dar el nombre a la lista.
