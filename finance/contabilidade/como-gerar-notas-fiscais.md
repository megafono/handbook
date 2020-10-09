# Como gerar notas fiscais?

**Metabase**

Os dados da nota fiscal estará no Metabase, por ex: CNPJ, descrição do serviço, valor da nota, link admin, nome, e-mail, etc, bem como quais clientes tem notas fiscais pendentes.

Esses dados será necessário para preencher os campos na hora de gerar as notas fiscais no Contabilizei.

**Contabilizei**

O contabilizei é a ferramenta de contabilidade que usamos para gerar as notas fiscais.

### Passo a Passo Emissão

1. Entre no Contabilizei
2. Entre no menu "Notas Fiscais &gt; Emitir NFs-e" 
3. Clique em "Cadastrar novo cliente" 
4. Preencha o campo "CNPJ\*" e aperte o "Tab" para preencher automaticamente os dados do cliente
5. Em "Características da Atividade" selecione o imposto de 15%
6. Em "Descrição do serviço e formas de pagamento\*" é necessário copiar a descrição do serviço que está no Metabase
7. Em "Valor" preencher o valor do pacote de serviço que o cliente contrato, este valor estará no Metabase da mesma forma que o CNPJ e os demais dados.
8. Clique em "Emitir nota fiscal"

Depois de emitida é precisa dar baixa no sistema do Megafono, para isso siga o passo a passo a seguir

1. No Metabase, na visão de nota fiscal pendente, tem a coluna "Link do admin", clique nesse link.
2. Em "Tax document status" escolha a opção "send"
3. Clique em "Save"

