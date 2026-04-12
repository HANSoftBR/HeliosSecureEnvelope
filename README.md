# Helios Secure Envelope
**Status:** Descontinuado  
Este projeto não está mais em desenvolvimento ou manutenção ativa.

> **Status:** Descontinuado  
> Este projeto não está mais em desenvolvimento ou manutenção ativa.

**Versão:** 1.0.0  
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

# AVISO DE RESPONSABILIDADE

Este software é fornecido **"no estado em que se encontra" ("AS IS")**, sem garantias de qualquer tipo, expressas ou implícitas.

O **Helios Secure Envelope** é uma ferramenta destinada a auxiliar na proteção e ocultação de dados, porém **não garante proteção absoluta contra todos os tipos de ataques, análises forenses ou falhas de sistema**.

O desenvolvedor **não se responsabiliza por perda de dados, falhas de uso, uso inadequado ou acesso não autorizado às informações protegidas**.

Ao utilizar este software, o usuário reconhece e aceita estes termos.

---

# LICENÇA

Este software é distribuído sob **Licença Proprietária HANSoft**.

O código-fonte, algoritmos, interface e mecanismos de segurança permanecem propriedade intelectual exclusiva da **HANSoft**.

Consulte o arquivo **LICENSE** para mais detalhes.

---

© 2026 HANSoft
