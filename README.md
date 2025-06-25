# clase03-2bim

imagen esplicacion

![alt text](image-1.png)

busca la relacion en el modelo y lo referencia con el set_ y si no encuentra esa relacion deja pasar y no genera ningun error


### 25 Junio del 2025

La clase numerotelefonicpEstudiantesForm asocia automaticamente un numero telefonico con un estudiante si que el usuario lo seleccione, usa un constructor personalizado donde se se trae un parametro estudiante, llama al constructor con esto     super(NumeroTelefonicoEstudianteForm, self).__init__(*args, **kwargs), inicializa el formulario.
self.initial['estudiante'] = estudiante establece el valor inicial con el objeto que se le paso, cambia el widget del campo estudiantepara que se amuestre como un campo oculto con hidden elf.fields["estudiante"].widget = forms.widgets.HiddenInput().
