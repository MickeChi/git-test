# Comandos útiles de Git

1. git init

2. git add .

3. git reset .

4. git commit -m "este es el mensaje

5. git checkout --m . | restaura el repositorio al ultimo commit

6. git log | muestra el log de commits    

7. git commit -amend

8. git branch  | muestra todas las ramas disponibles 

9. git checkout -b nombre-rama | crea rama y hace checkout

10. git checkout nombre-rama | hace checkout en rama

11. git merge nombre-rama | hacemos merge de la rama mencionada en la rama current checkout

11. git branch -d nombre-rama | elimina una rama

12. agregar repo local a repositorio github
    - git remote add origin https://github.com/MickeChi/git-test.git
    - git branch -M main | renombra master a main
    - git push -u origin main | sube cambios al repositorio remoto

13. git push | sube los cambios de la rama current a su equivalente en repositorio remoto

14. git commit -am "cambios de nuevo comanto" | atajo para git add. y git commit m

# Flujo git flow con comandos git
    https://gist.github.com/JamesMGreene/cdd0ac49f90c987e45ac
    https://www.atlassian.com/es/git/tutorials/comparing-workflows/gitflow-workflow