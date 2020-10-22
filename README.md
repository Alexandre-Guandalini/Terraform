# Examen Gitlab  

## L'Infrastructure As Code avec Terraform sur le cloud AWS

* Création d'un projet Terraform sur Gitlab.com sur l'installation d'une infrastructure pour la partie OPS.
* Pour l'infrastructure, la chaine sera composée des étapes suivantes :
	* `test` qui executera une validation local des fichiers Terraform
	* `apply` qui lui permettera de déployer l'infrastructure et sotckera les fichiers `terraform.tfstate` dans un artefact (15 jours de conservation)
	* `destroy` qui va permettre de supprimer l'infrastructure

