# 📝 Relatório do Laboratório 1 - Introdução ao Linux

**Nome:** Eduardo Kenzo Okada
**RA:** 10723321 

---

## 💡 Orientações Importantes
Este relatório é sua oportunidade de documentar não apenas o que você fez, mas principalmente o que você aprendeu. Como temos apenas um encontro semanal, é importante que você seja o(a) protagonista do seu aprendizado.

Para elaborar um relatório completo e que realmente agregue valor ao seu aprendizado, siga estas dicas:

- 📚 **Vá além do repositório**: Os materiais fornecidos são apenas o ponto de partida. Busque vídeos no YouTube, tutoriais, documentações oficiais e artigos que expliquem os conceitos de diferentes perspectivas.
- 🔍 **Seja curioso**: Quando encontrar um comando novo, não apenas execute-o - entenda o que ele faz, suas opções e em que situações reais ele é utilizado.
- 💭 **Conecte com a realidade**: Pesquise como empresas como Netflix, Google e Amazon utilizam Linux em seus servidores. Isso tornará o aprendizado mais tangível e relevante para sua carreira.
- 🎯 **Pratique além do lab**: Instale uma VM em casa, experimente distribuições diferentes, quebre coisas e conserte - é assim que se aprende de verdade!
- 🤝 **Compartilhe conhecimento**: Encontrou um tutorial bacana? Um comando útil? Compartilhe com seus colegas! O aprendizado colaborativo acelera o desenvolvimento de todos.

- **Lembre-se**: Em TI, a capacidade de aprender por conta própria é tão importante quanto o conhecimento técnico. Use este laboratório como uma oportunidade para desenvolver ambas as habilidades. Profissionais que sabem buscar, filtrar e aplicar informações são os mais valorizados no mercado!

## 1️⃣ Parte 1 - Experiência com Comandos Básicos

### 🔍 Primeiras Impressões

**1. Qual foi o comando mais útil que você aprendeu? Por quê?**

```
O comando `ls -la`, porque além de listar os arquivos, mostra permissões, tamanhos e datas de modificação. Isso ajuda a entender melhor o que está acontecendo no sistema e a ter mais controle sobre os arquivos.

```

**2. Qual comando você achou mais difícil de entender? Por quê?**

```
O `chmod`, porque envolve entender bem como funcionam as permissões de leitura, escrita e execução no Linux, tanto em forma numérica (777, 644, etc.) quanto simbólica (rwx).

```

**3. Você conseguiu completar todos os exercícios? Se não, quais dificuldades encontrou?**

```
Sim, consegui completar, mas no início tive dificuldade em lembrar a diferença entre `cp` e `mv`, já que um copia e o outro move/renomeia.

```

---

## 2️⃣ Parte 2 - Comparação Windows vs Linux

### 💻 Diferenças Observadas

**1. Liste 3 diferenças principais entre usar Windows e Linux que você notou:**

```
1. Linux tem licença aberta
2. O Linux é baseado em diretórios e arquivos para praticamente tudo (inclusive dispositivos), enquanto no Windows os dispositivos aparecem como letras de disco.
3. O Linux tem mais liberdade de customização e controle, mas exige mais conhecimento técnico.

```

**2. Para tarefas do dia a dia, qual sistema você prefere? Por quê?**

```
Windows pois sempre tive habito de usar o mesmo
```

**3. Em que situações o Linux seria mais vantajoso que o Windows?**

```
Em servidores, desenvolvimento de software, segurança da informação e quando é necessário automatizar tarefas rotineiras.

```

---

## 3️⃣ Parte 3 - Reflexões sobre Sistemas Operacionais

### 🎯 Importância para SI

**1. Por que é importante para um profissional de Sistemas de Informação conhecer Linux?**

```
Porque grande parte dos servidores e serviços no mundo rodam em Linux. Além disso, o conhecimento em Linux permite entender melhor como funcionam processos, redes e segurança.
```

**2. Como o conhecimento de comandos Linux pode ajudar na gestão de TI de uma empresa?**

```
Ajuda a automatizar tarefas, monitorar servidores, resolver problemas rapidamente e garantir maior controle sobre o ambiente. 
Um administrador que domina Linux consegue gerenciar infraestrutura de forma mais eficiente e segura.

```

**3. Cite 3 aplicações práticas do Linux no ambiente empresarial:**

```
1. Servidores web (Apache, Nginx).
2. Bancos de dados (MySQL, PostgreSQL).
3. Ferramentas de segurança e monitoramento (firewalls, logs e scripts de automação).

```

---

## 4️⃣ Parte 4 - Comandos e Outputs

### 📊 Análise dos Resultados

**1. Quantos arquivos você criou no diretório `outputs/`?**

```
Total de arquivos: 5
```

**2. Qual foi o tamanho total do diretório `meu_diretorio` que você criou?**

```bash
# Use o comando: du -sh meu_diretorio/
Tamanho: 12k
```

**3. Liste os 5 comandos que você mais usou durante o laboratório:**

```
1. ls
2. cd
3. mkdir
4. touch
5. cat

```

---

## 5️⃣ Parte 5 - GitHub e Versionamento

### 🔧 Experiência com Git

**1. Você já tinha usado Git antes? Se sim, em que contexto?**

```
Somente na aula de web mobile, para enviar os exercicios
```

**2. Qual a importância do versionamento de código para empresas?**

```
O versionamento permite que várias pessoas trabalhem juntas no mesmo projeto sem perder histórico de alterações. 
Isso aumenta a organização, evita retrabalho e garante que sempre seja possível voltar a versões anteriores. 
Além disso, é essencial para o controle de qualidade e colaboração em grandes equipes.

```

---

## 6️⃣ Parte 6 - Aplicações Futuras

### 🚀 Próximos Passos

**1. Que tipo de tarefas você poderia automatizar usando comandos Linux?**

```
1. Backup automático de arquivos e diretórios.
2. Monitoramento de uso de disco e envio de alertas por e-mail.
```

**2. Você consideraria usar Linux como sistema operacional principal? Por quê?**

```
Sim, principalmente se for para estudos, desenvolvimento e uso profissional. Ele é estável, seguro e gratuito. 
Mas ainda manteria o Windows em paralelo para jogos e softwares específicos.

```

---

## 💡 Feedback do Laboratório

**O que você achou mais interessante no laboratório?**

```
Aprender a navegar apenas pelo terminal e perceber como os comandos básicos já permitem bastante controle sobre o sistema.

```

**O que poderia ser melhorado para próximos labs?**

```
Mais exemplos práticos de uso real em empresas, como administração de servidores e automação de rotinas.

```

---

## 📤 Checklist Final

Antes de enviar, verifique:

- [ ] Preenchi todas as seções do relatório
- [ ] Completei todos os exercícios em EXERCICIOS.md
- [ ] Salvei todos os outputs na pasta outputs/
- [ ] Criei o diretório meu_diretorio com os arquivos solicitados
- [ ] Fiz git add, commit e push

---