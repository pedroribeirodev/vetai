# VetAI Prompts

Prompt templates para clínicas veterinárias usando LLMs.

Projeto criado durante minha trilha de estudos em IA aplicada — focado em aplicar prompt engineering em cenários reais.

## Templates

| Template | O que faz |
|---|---|
| [Laudo de Hemograma](laudo-hemograma.md) | Traduz valores de hemograma para linguagem acessível ao tutor |
| [Orientação Pós-Cirúrgica](orientacao-pos-cirurgica.md) | Gera instruções de cuidados pós-operatórios personalizadas por animal e procedimento |
| [Resumo de Prontuário](resumo-prontuario.md) | Cria resumo estruturado para passagem de plantão entre veterinários |

## Como usar

1. Copie o prompt do template
2. Substitua as variáveis (`{{VARIAVEL}}`) pelos dados reais
3. Cole no Claude, GPT-4 ou outro LLM

## Patterns utilizados

- **System prompt** com papel definido e restrições claras
- **Structured output** com seções pré-definidas
- **Guardrails** para evitar diagnósticos definitivos
- **XML tags** para delimitar input e output

## Stack

Testado com Claude (Anthropic) e GPT-4 (OpenAI). Os templates são provider-agnostic.

---

Parte da minha [trilha de estudos em IA aplicada](https://github.com/SEU_USER/trilha-ia-aplicada).
