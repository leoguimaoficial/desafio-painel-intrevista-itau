# **Gama Academy - Transformando Talentos para o Futuro**

### **Autor**
 Leonardo Guimarães da Silva
[LinkedIn](https://www.linkedin.com/in/leonardo-guimaraes-3191751ab/)
[GitHub](https://github.com/leoguimaoficial)
## **Desafio Cadastro Pessoal - Atração**

Criar um formulário para registrar dados pessoais

### **Implementação**
* Projeto implementado com HTML5 e JavaScript.
* Utilização das normas de acessibilidade W3C.
* Campos obrigatórios definidos com required do HTML5.
* O select foi utilizado para o sexo, com duas opções.
* Adicionado botão de limpar os dados com o type reset
* JS adicionado na mesma página para facilitar na apresentação.
* Ao enviar o formulário, é mostrada uma mensagem perguntando o envio da requisição pelo usuário (Confirm)
* Ao confirmar o envio, uma mensagem com o nome do usuário agradecendo o envio é mostrada. (variável 'nome' é utilizada do formulário).
* Para definir o número do endereço, o type number foi utilizado para bloquear o uso de letras.
* Campos do telefone fixo e celular o type tel foi utilizado, para facilitar a digitação nos dispositivos móveis.
* Ao digitar um CEP válido, os campos de endereço, bairro, cidade e estado é preenchido automaticamente por uma requisição Json. A API [ViaCEP](https://viacep.com.br/) foi utilizada.
* Possibilidade de preencher os campos de endereço, caso o usuário não queira digitar um CEP.
* Ao limpar o formulário, uma mensagem de confirmação novamente é mostrada perguntando se deseja realmente realizar o reset.
* Para facilitar os usuários, os campos obrigatórios estão com * para chamar a atenção.
* Footer adicionada com LinkedIn e Github do Autor.

### **Campos do projeto**
- [ ]  Cadastro Pessoal com os campos: Nome, Cpf, Rg, Sexo, Endereco, Numero, Bairro, Cidade, Estado, Cep, Telefone Fixo, Telefone Celular.

### **Regra de Negócio**

1. Os campos Nome, Cpf, Endereco, Numero, Telefone Celular são obrigatórios

### **Requisitos**

1. Explorar os recursos de CSS
2. Explorar os recursos do Javascript (Ex. Abrir um alert ao submeter o formulário)
3. Hospedar o site! (Sugerimos o Netlify que é gratuito)

### **Extras**

1. O campo Sexo pode ser do tipo select com com as opções M = Masculino, F = Feminino
2. Estilização do site (CSS) básico
3. Disponibilizar o link do github do projeto bem descrito quanto às funcionalidades, implementações relevantes e links de pesquisas

### **Orientações**

- O desafio é individual
- Não usar frameworks de estilo como Bootstrap, Google Material e demais.
- Os entregáveis descritos acima são requisitos básicos para apresentação no dia da entrevista, ficando a critério do candidato, se quiser e estiver apto a melhorar o desafio de alguma forma, com os conhecimentos adquiridos durante a trilha de especialização.