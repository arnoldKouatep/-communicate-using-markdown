# Step 1

# Ceci est un entete de taille H1
## Ceci est un entete de taille H2
### Ceci est un entete de taille H3
#### Ceci est un entete de taille H4
##### Ceci est un entete de taille H5
###### Ceci est un entete de taille H6

# Step 2

![Image de fleurs](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTvSHiIcQXPv35K3tXHTXfhElY90rma09JIOMb83VIV&s)

# Step 3
```
TEMPLATES = [
    {
        'BACKEND': 'django.template.backends.django.DjangoTemplates',
        'DIRS': [os.path.join(BASE_DIR, 'templates')],
        'APP_DIRS': True,
        'OPTIONS': {
            'context_processors': [
                'django.template.context_processors.debug',
                'django.template.context_processors.request',
                'django.contrib.auth.context_processors.auth',
                'django.contrib.messages.context_processors.messages',
            ],
        },
    },
]
```
