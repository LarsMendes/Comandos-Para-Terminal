
# Comandos para Terminal: Vocabulário de Navegação e Manipulação de Arquivos


O compilado de comandos abaixo foi escrito para facilitar o aprendizado durante sua jornada no estudo de programação e versionamento de código. Confira também abaixo:


## 🧭 Comandos de Navegação
```
cd [diretorio]: Muda o diretório de trabalho atual para o especificado.
cd ~: Vai para o diretório home do usuário
cd ..: Vai para o diretório pai.
cd -: Volta para o último diretório acessado.
```

## 📋 Listagem de Arquivos e Diretórios
```
ls : Lista arquivos e diretórios no diretório atual.
ls -a: Exibe todos os arquivos, incluindo os ocultos.
ls -l: Exibe delhas (como permissões, proprietário, tamanho) de cada arquivo.
ls -lh: Lista arquivos em formato legível (em KB, MB, etc.).
ls -R: Lista recursivamente todos os arquivos e subdiretórios.
```

## 📂 Manipulação de Arquivos e Diretórios
```
mkdir [nome]: Crie um novo diretório (pasta) com o nome especificado.
rmdir [diretório]: Remove um diretório vazio.
rm [arquivo]: Remove um arquivo.
rm -r [diretório]: Remove um diretório e seu conteúdo recursivamente.
rm -f [arquivo]: Força a remoção, ignorando confirmações.
```

## 🚀 Copiar e Mover Arquivos
```
cp [origem]: Copia arquivos ou diretórios.
cp -r [diretório_origem] [diretório_destino]: Copia um diretório e seus conteúdos recursivamente.
mv [origem][destino]: Move ou renomeia arquivos e diretórios.
```

## 👁 Visualização de Arquivos
```
cat [arquivo]: Exibe o conteúdo de um arquivo.
more [arquivo]: Exibe o conteúdo de um arquivo página por página.
less [arquivo]: Exibe o conteúdo de um arquivo com rolagem (mais avançado que o more).
head [arquivo]: Exbie as primeiras 10 linhas de um arquivo.
tail [arquivo]: Exibe as útimas 10 linhas de um arquivo.
tail -f [arquivo]: Exibe as atualizações em tempo real (útil para logs).
```

## 💻 Informações do Sistema
```
pwd: Exibe o diretório de trabalho atual.
whoami: Exibe o nome do usuário atual.
uname -a: Exibe o uso de espaço em disco de forma legível.
df -h: Exibe o uso de espaço em disco de forma legível.
du -h [arquivo ou diretório]: Exibe o uso de espaço do arquivo ou diretório especificado.
```

## 🔎 Busca
```
find [caminho] -name [nome_do_arquivo]: Procura um arquivo ou diretório específico.
grep [opções] [palavra] [arquivo]: Procura por uma palavra ou padrão específico em um arquivo.
grep -i: Ignora diferenciação entre maiúsculas e minúsculas.
grep -r [palavra] [diretório]: Procura recursivamente no diretório.
```

## ✅ Permissões no Arquivo
```
chmod [permissões][arquivo]: Altera permissões de um arquivo (por exemplo, chmod 755: permissão de execução e leitura)
chown [usuário]: [grupo] [arquivo]: Altera o dono e grupo de um arquivo ou diretório.
```

## 📚 Processos
```
ps: Exibe uma lista de processos em execução
top: Exibe em tempo real os processos ativos.
kill [PID]: Encerra um processo pelo seu ID.
kill -9 [PID]: Força o encerramento do processo.
```

## 📦 Comandos de Compressão e Descompressão
```
tar -cvf arquivo.tar [diretório ou arquivos]: Cria um arquivo tar
tar -xvf arquivo.tar: Extrai um arquivo tar.
tar -czvf arquivo.tar.gz [diretório ou arquivos]: Cria um arquivo tar comprimido com gzip.
tar -xzvf arquivo.tar.gz: Extrai um arquivo tar comprimido com gzip.
```

## Referência

 - [Desenvolvimento Java com IA](https://web.dio.me/track/coding-future-gft-desenvolvimento-java-com-ia)

