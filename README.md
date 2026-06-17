# Chatbot para Geração de Casos de Teste e Testes Automatizados com IA

---

#### Projeto da Disciplina PET1706 - TÓPICOS ESPECIAIS EM ENGENHARIA DE SOFTWARE (Redes Neurais Artificiais) - 2026.1
###### Professora: Rosana Rego

<div align="center">
  <img src="https://raw.githubusercontent.com/roscibely/algorithms-and-data-structure/main/root/ufersa.jpg" width="700" height="250">
</div>

<p align="center">
  <i>
    <a href="https://engsoftwarepaudosferros.ufersa.edu.br/apresentacao/">
      Curso Bacharelado em Engenharia de Software
    </a>
    - UFERSA Campus Pau dos Ferros
  </i>
</p>

---

Este projeto consiste em um chatbot inteligente desenvolvido para auxiliar atividades de teste de software por meio de Modelos de Small Language Model (SLM).

A aplicação identifica automaticamente se a entrada fornecida pelo usuário corresponde a um requisito textual ou a um trecho de código-fonte. Com base nessa identificação, o sistema é capaz de gerar casos de teste ou testes automatizados com PyTest.

O chatbot utiliza o modelo **Qwen2.5-1.5B-Instruct**, disponibilizado pela Hugging Face.

## 🚀 Funcionalidades

- **Geração Automática de Casos de Teste**: A partir de requisitos funcionais descritos em linguagem natural, o sistema gera casos de teste contemplando casos positivos, casos negativos, cestes de limite (Boundary Testing), resultados esperados.
- **Geração de Testes Automatizados**: Ao receber um trecho de código, o chatbot gera automaticamente testes utilizando o framework **PyTest**.
- **Detecção Automática do Tipo de Entrada**: O sistema identifica automaticamente se o texto enviado corresponde a um requisito funcional ou a um trecho de código.

### 📊 Métricas de Desempenho

Durante a execução são coletadas métricas como:

- Tokens de entrada;
- Tokens de saída;
- Tempo de resposta;
- Tokens processados por segundo.

## 🛠️ Tecnologias Utilizadas

- Python 3.10+
- PyTorch
- Transformers
- Hugging Face
- Qwen2.5-1.5B-Instruct
- PyTest

## 🧠 Modelo Utilizado

### Qwen2.5-1.5B-Instruct

Modelo de linguagem otimizado para:

- Seguir instruções;
- Geração de texto;
- Assistência ao desenvolvimento de software;
- Produção de artefatos de testes.

Link do modelo:

https://huggingface.co/Qwen/Qwen2.5-1.5B-Instruct

## Contribuição

Contribuições são bem-vindas! Se você quiser contribuir para este projeto, por favor, abra uma issue para discutir as mudanças propostas ou envie um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT). Consulte o arquivo `LICENSE` para obter mais detalhes.

## Equipe
<table align="center">
  <tr>    
    <td align="center">
      <a href="https://github.com/angellusj">
        <img src="https://avatars.githubusercontent.com/u/123104907" 
        width="120px;" alt="Foto de Ângela M. A. Aquino no GitHub"/><br>
        <sub>
          <b>Ângela M. A. Souza</b>
         </sub>
      </a>
    <td align="center">
      <a href="https://github.com/Malicef">
        <img src="https://avatars.githubusercontent.com/u/123081912" 
        width="120px;" alt="Foto de Maria A. F. Teixeira no GitHub"/><br>
        <sub>
          <b>Maria A. F. Teixeira</b>
         </sub>
      </a>
    </td>
  </tr>
</table>
