# warning: adding embedded git repository: client  

hint: You've added another git repository inside your current repository.  

hint: Clones of the outer repository will not contain the contents of  

hint: the embedded repository and will not know how to obtain it.  

hint: If you meant to add a submodule, use:  

hint:  

hint:   git submodule add <url> client  

hint:  

hint: If you added this path by mistake, you can remove it from the  

hint: index with:  

hint:  

hint:   git rm --cached client  

hint:  

hint: See "git help submodule" for more information.  

# una solucion

git rm --cached nombre_carpeta  

git commit -m "remove cached repo"  

git add nombre_carpeta/  

git commit -m "Add folder"  

git push  

