# Trabalho realizado na Semana #3

## Identificação

- Existe uma vulnerabilidade de execução remota de código no software Microsoft Outlook
 quando este não consegue lidar com os objetos na memória de forma adequada.
- Um atacante que explorar com sucesso a vulnerabilidade pode executar
 código arbitrário no contexto da vítima.
- Esta vulnerabilidade afeta a Microsoft e o Outlook.

## Catalogação

- Reportado à Microsoft pelo 0neb1n a partir do Zero Day Initiative (2020-07-01).
- CVE-2020-16947
- CVSS Score: 8.1 (HIGH)

## Exploit

- A falha específica existe na análise de conteúdo HTML no e-mail.
- Um atacante pode explorar a vulnerabilidade enviando ao utilizador por email um 
ficheiro especialmente criado e convencê-lo a abri-lo.
- A interação do utilizador é necessária, pois este deve abrir o e-mail, ou
vizualizá-lo no painel de pré-visualização.

## Ataques

- Existe proof-of-concept code, mas não encontramos relatos de um exploit a esta 
vulnerabilidade.
- No entanto o potencial para danos pode ser grande.
- Se a vítima tiver direitos administrativos, um atacante pode assumir
o controlo do sistema afetado.
- A partir daí pode instalar programas; vizualizar, alterar ou excluir dados;
ou criar novas contas com direitos totais de utilizador.
