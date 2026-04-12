# Helios Secure Envelope
**Status:** Descontinuado  
Este projeto não está mais em desenvolvimento ou manutenção ativa.

> **Status:** Descontinuado  
> Este projeto não está mais em desenvolvimento ou manutenção ativa.

**Versão Atual:** 3.1.0  
**Autor:** HANSoft  
**Contato:** devhansoft@gmail.com  
**Licença:** Licença Proprietária HANSoft  

---

# DESCRIÇÃO

O **Helios Secure Envelope** utiliza técnicas modernas de criptografia em múltiplas camadas para proteger informações sensíveis.

O sistema permite unir arquivos sem comprometer a integridade do arquivo base, mantendo-o funcional e intacto.

Enquanto isso, o conteúdo oculto é protegido por camadas avançadas de criptografia, dificultando engenharia reversa e garantindo sigilo.

---

# RECURSOS DE SEGURANÇA

Recursos de segurança utilizados:

- Verificação de integridade
- Cascading encryption com **AES** e **ChaCha20**
- Autenticação **HMAC-SHA256**
- Técnicas de ofuscação de dados
- Particionamento de constantes
- Inserção de bytes aleatórios
- Codificação customizada

---

# INTEGRIDADE DO ARQUIVO BASE

Durante a combinação, o arquivo principal permanece funcional e inalterado em sua estrutura original.

Isso garante que ele possa ser aberto, visualizado e utilizado normalmente após o processo.

---

# FORMATOS RECOMENDADOS COMO BASE

### Imagens
- PNG
- JPG
- JPEG
- SVG
- TIFF

### Vídeos
- MP4
- AVI
- MOV
- WMV

### Áudio
- MP3
- WAV
- FLAC

### Documentos
- PDF

---

# SOBRE OS FORMATOS

Formatos mais adequados como **Arquivo Base** incluem imagens, vídeos, áudios e PDFs, pois normalmente toleram dados extras ao final do arquivo.

Formatos que dependem de estrutura rígida como:

- ZIP
- RAR
- 7Z
- DOCX
- XLSX

devem ser evitados como base, pois podem ser corrompidos ao receber dados anexados.

---

# ARQUIVO OCULTO

O arquivo oculto pode possuir **qualquer formato**, como:

- documentos
- imagens
- vídeos
- backups
- arquivos compactados

**Limite do arquivo oculto:** até **2 GB**.

---

# REGRAS DE SEGURANÇA

Por motivos de segurança, o software **bloqueia o uso de executáveis e scripts** nas seleções de arquivo.

---

# AVISO LEGAL

O **Helios Secure Envelope** é fornecido **"no estado em que se encontra"** (**"AS IS"**), de acordo com suas funcionalidades normais e limitações técnicas previsíveis, **sem garantias de qualquer tipo**, expressas ou implícitas.

Este software destina-se à **combinação e proteção de conteúdos** por técnicas criptográficas e mecanismos auxiliares descritos em sua documentação, buscando preservar, dentro de sua proposta funcional, a utilização normal do arquivo base.

O desenvolvedor não garante:

- proteção absoluta contra acesso indevido;
- ausência total de falhas, erros, bugs ou vulnerabilidades;
- funcionamento ininterrupto;
- compatibilidade universal com todos os formatos de arquivo, leitores, sistemas, verificadores, mecanismos de inspeção, antivírus, compactadores ou ambientes de execução;
- que o arquivo resultante será aceito, interpretado ou executado normalmente em todo e qualquer sistema, aplicação, política corporativa, filtro de segurança ou ambiente de terceiros;
- recuperação integral de dados em caso de falha grave;
- imunidade contra comprometimentos causados pelo ambiente do usuário.

Bugs, falhas e comportamentos inesperados **podem existir e podem ocorrer durante o uso**, mesmo com testes e cuidados no desenvolvimento. Nenhum software é totalmente livre de erros.

## Limitação de responsabilidade

Na máxima extensão permitida pela legislação aplicável, o desenvolvedor não se responsabiliza por:

- perda de dados;
- uso inadequado do software;
- falhas, bugs ou comportamentos inesperados;
- falhas no ambiente do usuário;
- danos decorrentes de configuração insegura do dispositivo;
- problemas causados por softwares de terceiros;
- corrupção de arquivos;
- incompatibilidades com sistemas, programas, políticas de segurança ou ambientes externos;
- comprometimento externo do sistema.

Isso inclui, entre outros fatores:

- malware;
- keyloggers;
- acesso físico ao dispositivo;
- captura indevida de tela;
- engenharia social;
- interrupção elétrica;
- falhas do sistema operacional;
- corrupção de dados;
- exclusão indevida;
- erro humano;
- uso inseguro do equipamento;
- interferência de antivírus, filtros ou softwares de terceiros.

## Responsabilidade do usuário

O usuário é responsável por:

- testar previamente o arquivo gerado em **ambiente controlado** antes de utilizá-lo em fluxo real;
- manter cópia do **arquivo original** antes de qualquer operação;
- manter backup do conteúdo relevante antes de combinar, exportar ou processar arquivos;
- verificar se o resultado atende às necessidades do seu ambiente e da sua finalidade de uso.

---

**Importante:** nenhum software pode oferecer garantia absoluta de segurança, compatibilidade universal ou recuperação total de dados em todos os cenários.

---

# LICENÇA

Este software é distribuído sob **Licença Proprietária HANSoft**.

O código-fonte, algoritmos, interface e mecanismos de segurança permanecem propriedade intelectual exclusiva da **HANSoft**.

Consulte o arquivo **LICENSE** para mais detalhes.

---

© 2026 HANSoft
