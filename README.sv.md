# dcs-scripts

[English](README.md) | **Svenska**

## Kom igång

Du behöver [Git](https://git-scm.com/downloads) och ett [GitHub](https://github.com)-konto.

### 1. Klona repot

När du klonar laddar du ner en kopia av repot till din dator:

```sh
git clone https://github.com/Nosigswe/dcs-scripts.git
cd dcs-scripts
```

### 2. Skapa en branch

Jobba inte direkt på `main`. Skapa en branch för din ändring och ge den ett kort, beskrivande namn:

```sh
git checkout -b min-andring
```

### 3. Gör och committa dina ändringar

Redigera filerna och spara sedan ditt arbete i en commit:

```sh
git add .
git commit -m "Beskriv vad du ändrade"
```

### 4. Pusha din branch till GitHub

```sh
git push -u origin min-andring
```

Om du inte har skrivrättigheter till repot behöver du först [forka det](https://docs.github.com/sv/get-started/quickstart/fork-a-repo) på GitHub, klona din fork och pusha dit i stället.

### 5. Skapa en pull request

1. Gå till https://github.com/Nosigswe/dcs-scripts.
2. GitHub visar knappen **Compare & pull request** för din nyligen pushade branch. Klicka på den.
3. Skriv en titel och en kort beskrivning av vad du ändrade och varför.
4. Klicka på **Create pull request**.

Någon kommer att granska din pull request. Om du ombeds göra ändringar gör du dem på samma branch, committar och pushar igen. Din pull request uppdateras automatiskt.
