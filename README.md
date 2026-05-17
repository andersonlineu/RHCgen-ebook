# RHCgen: E-book

> **Um Pacote R para Automação, Padronização e Avaliação da Qualidade dos Dados do Registro Hospitalar de Câncer no Brasil**

[![GitHub Pages](https://img.shields.io/badge/E--book-GitHub%20Pages-blue?logo=github)](https://andersonlineu.github.io/RHCgen-ebook/)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.19962293-blue)](https://doi.org/10.5281/zenodo.19962293)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

---

## 📖 Acesse o e-book

👉 **https://andersonlineu.github.io/RHCgen-ebook/**

---

## Sobre

Este repositório contém o código-fonte do e-book da nota técnica do **RHCgen**, um pacote computacional de acesso aberto implementado na linguagem R, voltado à automação, padronização e avaliação da qualidade dos dados do **Registro Hospitalar de Câncer (RHC)** no Brasil.

O e-book foi desenvolvido com [Quarto](https://quarto.org/) e publicado via GitHub Pages.

---

## Autores

| Autor | ORCID | Afiliação |
|-------|-------|-----------|
| Anderson Lineu Siqueira dos Santos | [![ORCID](https://img.shields.io/badge/ORCID-0000--0002--1703--9310-brightgreen?logo=orcid)](https://orcid.org/0000-0002-1703-9310) | ENSP/Fiocruz, Rio de Janeiro, Brasil |
| Tatyellen Natasha da Costa Oliveira | [![ORCID](https://img.shields.io/badge/ORCID-0000--0002--4781--3952-brightgreen?logo=orcid)](https://orcid.org/0000-0002-4781-3952) | ENSP/Fiocruz; IEC, Ananindeua, PA, Brasil |
| Raphael de Freitas Saldanha | [![ORCID](https://img.shields.io/badge/ORCID-0000--0003--0652--8466-brightgreen?logo=orcid)](https://orcid.org/0000-0003-0652-8466) | ICICT/Fiocruz, Rio de Janeiro, Brasil |
| Raquel de Vasconcellos Carvalhaes de Oliveira | [![ORCID](https://img.shields.io/badge/ORCID-0000--0001--9387--8645-brightgreen?logo=orcid)](https://orcid.org/0000-0001-9387-8645) | INI/Fiocruz, Rio de Janeiro, Brasil |

---

## Conteúdo

1. Introdução
2. Fonte de Dados: o Registro Hospitalar de Câncer
3. Desenvolvimento do RHCgen
4. O *Pipeline* de Processamento
5. Leitura e Integração dos Arquivos DBF
6. Padronização das Variáveis
7. Recodificação das Variáveis Categóricas
8. Harmonização Territorial das Variáveis Geográficas
9. Padronização de Códigos Clínicos e Assistenciais
10. Avaliação da Qualidade dos Dados
11. Aplicação
12. Discussão
13. Conclusão
14. Guia Prático de Instalação e Uso

---

## Pacote RHCgen

O pacote está disponível no GitHub:

👉 **https://github.com/andersonlineu/RHCgen**

Para instalar:

```r
# Instalar o pacote remotes (caso não tenha)
install.packages("remotes")

# Instalar o RHCgen
remotes::install_github("andersonlineu/RHCgen")
```

---

## Como citar

> Santos, A. L. S. dos., Oliveira, T. N. da C., Saldanha, R. de F., & Oliveira, R. de V. C. de. (2026). *RHCgen: Um Pacote R para Automação, Padronização e Avaliação da Qualidade dos Dados do Registro Hospitalar de Câncer no Brasil.* Zenodo. https://doi.org/10.5281/zenodo.19962293

---

## Tecnologias utilizadas

- [R](https://www.r-project.org/)
- [Quarto](https://quarto.org/)
- [GitHub Pages](https://pages.github.com/)
