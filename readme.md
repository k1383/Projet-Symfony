## Créer un projet Symfony 

- Créer un dossier
    - dans le Terminal ou PowerrShell

```bash
composer create-project symfony/website-skeleton projet-symfony
```

- Vérification de l’installation

```bash
cd .\projet-symfony\
```

- Lancement du serveur 
```bash
symfony serve`
```

### Repository GitHub 
[Projet Symfony](https://github.com/k1383/Projet-Symfony)

### Structure du projet
```bash
templates/
├── base.html.twig
├── home.html.twig
├── about.html.twig
├── partials/
│   ├── _header.html.twig
│   └── _footer.html.twig
└── admin/
    └── layout.html.twig
```

### Création de deux pages statiques 
```bash
home_static.html
about_static.html
```