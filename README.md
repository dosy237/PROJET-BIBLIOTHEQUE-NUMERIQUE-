


Bibliothèque Numérique est une application full-stack complète permettant de gérer efficacement une bibliothèque. Elle offre un système d'emprunt de livres, de réservations, de gestion des utilisateurs et bien plus encore.
 ## Fonctionnalités Principales

Gestion des Livres : 

```bash
Catalogue complet avec recherche, filtres et catégories
Système d'Emprunt : Emprunts, retours, renouvellements et gestion des amendes
Réservations : Système de réservation pour les livres non disponibles
Authentification JWT : Sécurité robuste avec tokens d'accès et de rafraîchissement
Multi-Rôles : Utilisateur, Bibliothécaire et Administrateur
Avis et Notes : Les utilisateurs peuvent noter et commenter les livres
Interface Admin : Panneau d'administration Django complet
API RESTful : Documentation Swagger automatique

```

##  Architecture

```
digital-library/
│
├──  README.md                    
├──  GETTING_STARTED.md           
├──  ARCHITECTURE.md              
├──  .gitignore                   
├──  docker-compose.yml           
│
├──  backend/                     
│   ├──  README.md                
│   ├──  requirements.txt        
│   ├──  Dockerfile             
│   ├──  .env.example           
│   ├──  manage.py               
│   │
│   ├──  config/                  
│   │   ├── settings.py           
│   │   ├── urls.py              
│   │   ├── wsgi.py               
│   │   ├── asgi.py               
│   │   └── celery.py             
│   │
│   └──  apps/                   
│       │
│       ├──  accounts/          
│       │   ├── models.py         
│       │   ├── serializers.py    
│       │   ├── views.py          
│       │   ├── urls.py           
│       │   └── admin.py         
│       │
│       ├──  books/             
│       │   ├── models.py        
│       │   ├── serializers.py    
│       │   ├── views.py         
│       │   ├── urls.py           
│       │   └── admin.py         
│       │
│       ├── oans/             
│       │   ├── models.py        
│       │   ├── serializers.py   
│       │   ├── views.py          
│       │   ├── urls.py           
│       │   └── admin.py          
│       │
│       └── core/             
│           ├── permissions.py    
│           ├── pagination.py     
│           └── utils.py          
│
└──  frontend/                  
    ├──  README.md              
    ├──  package.json           
    ├──  Dockerfile            
    ├──  nginx.conf             
    ├── .env.example          
    │
    ├──  public/                
    │   ├── index.html            
    │   └── manifest.json         
    │
    └──  src/                   
        ├──  index.jsx          
        ├──  App.jsx           
        │
        ├──  components/        
        │   ├──  layout/       
        │   ├──  common/       
        │   └──  features/     
        │
        ├──  pages/             
        │   ├── Home.jsx        
        │   ├── BookList.jsx     
        │   ├── BookDetail.jsx   
        │   ├── Login.jsx       
        │   ├── Register.jsx     
        │   ├── Profile.jsx      
        │   ├── MyLoans.jsx      
        │   ├── MyReservations.jsx 
        │   ├── Dashboard.jsx    
        │   └── NotFound.jsx     
        │
        ├──  services/          
        │   ├── api.js           
        │   ├── authService.js   
        │   ├── bookService.js   
        │   └── loanService.js   
        │
        ├──  context/           
        │   ├── AuthContext.jsx  
        │   └── ThemeContext.jsx 
        │
        ├──  routes/           
        │   ├── AppRoutes.jsx    
        │   └── PrivateRoute.jsx 
        │
        └──  utils/             
            ├── constants.js     
            └── helpers.js      
```
## Prérequis

Python 3.11+
Node.js 18+
PostgreSQL 14+ (ou utiliser Docker)
Git
Stack Technologique


## Backend

Django 5.0, Django REST Framework
Base de données : PostgreSQL 15
Authentification : JWT (Simple JWT)
Documentation : drf-spectacular (Swagger)
Tâches async : Celery, Redis

## Frontend

Framework : React 18.2
Routing : React Router v6
UI : Material-UI (MUI)
HTTP Client : Axios
State Management : Context API, React Query
Formulaires : React Hook Form, Yup

## DevOps

Containerisation : Docker, Docker Compose
Serveur Web : Nginx (production)
WSGI : Gunicorn

  ## Auteurs
  
```
donfack synthia calorine  - Développeur principal - @dosy237
TCHOULA DINOU ARNAUD RAYAM -  developpeur - rayanebambino3-del

```
