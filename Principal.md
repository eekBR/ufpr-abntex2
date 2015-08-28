## main.tex ##

```
%% abtex2-modelo-trabalho-academico.tex, v-1.9.2 laurocesar
%% Copyright 2012-2014 by abnTeX2 group at http://abntex2.googlecode.com/ 
%%
%% This work may be distributed and/or modified under the
%% conditions of the LaTeX Project Public License, either version 1.3
%% of this license or (at your option) any later version.
%% The latest version of this license is in
%%   http://www.latex-project.org/lppl.txt
%% and version 1.3 or later is part of all distributions of LaTeX
%% version 2005/12/01 or later.
%%
%% This work has the LPPL maintenance status `maintained'.
%% 
%% The Current Maintainer of this work is the abnTeX2 team, led
%% by Lauro César Araujo. Further information are available on 
%% http://abntex2.googlecode.com/
%%
%% This work consists of the files 
% 
%          main.tex   programa principal
%      00-dados.tex   entrada de dados 
%    00-pacotes.tex   pacotes carregados no modelo
% 00-pretextual.tex   processamento dos elementos pre-textuais
%          UFPR.sty   ajusta do modelo canonico às normas  UFPR
%
%    referencias.bib
%
%
%
%------------------------------------------------------------------------
% ------------------------------------------------------------------------
% abnTeX2: Modelo de Trabalho Academico (tese de doutorado, dissertacao de
% mestrado e trabalhos monograficos em geral) em conformidade com 
% ABNT NBR 14724:2011: Informacao e documentacao - Trabalhos academicos -
% Apresentacao
% ------------------------------------------------------------------------
% ------------------------------------------------------------------------

\documentclass[
	% -- opções da classe memoir --
	12pt,				% tamanho da fonte
	openright,			% capítulos começam em pág ímpar (insere página vazia caso preciso)
	twoside,			% para impressão em verso e anverso. Oposto a oneside
	a4paper,			% tamanho do papel. 
	% -- opções da classe abntex2 --
	chapter=TITLE,		% títulos de capítulos convertidos em letras maiúsculas
	section=TITLE,		% títulos de seções convertidos em letras maiúsculas
	%subsection=TITLE,	% títulos de subseções convertidos em letras maiúsculas
	%subsubsection=TITLE,% títulos de subsubseções convertidos em letras maiúsculas
	% -- opções do pacote babel --
	english,			% idioma adicional para hifenização
	french, 			% idioma adicional para hifenização
	spanish,			% idioma adicional para hifenização
	brazil,				% o último idioma é o principal do documento
	%%%%%%%%%%%%
	%eek: colocação da opção para o sumario ter formatação tradicional
	sumario=tradicional             % título no formato tradicional
	]{abntex2}

\input{00-pacotes}
\input{00-dados}
\usepackage{UFPR}

% ----------------------------------------------------------
% Início do documento
% ----------------------------------------------------------

\begin{document}


\input{00-pretextual}

% ----------------------------------------------------------
% ELEMENTOS TEXTUAIS
% ----------------------------------------------------------
\textual
\pagestyle{textualUFPR}

% ----------------------------------------------------------
% Introdução (exemplo de capítulo sem numeração, mas presente no Sumário)
% ----------------------------------------------------------
%\chapter*[INTRODUÇÃO]{INTRODUÇÃO}
%\addcontentsline{toc}{chapter}{INTRODUÇÃO}
% ----------------------------------------------------------
%\input{cap01}
%\chapter{TESTE}
%\sigla{ABC}{Santo André, São Bernardo do Campo e São Caetano do Sul}
%\simbolo{$\alpha$}{alfa}{}

% ----------------------------------------------------------
% PARTE DA PREPARAÇÃO DA PESQUISA
% ----------------------------------------------------------
%\part{Preparação da pesquisa}
% ----------------------------------------------------------
%\input{cap02}
%
% ----------------------------------------------------------
% PARTE DOS REFERENCIAIS TEÓRICOS
% ----------------------------------------------------------
%\part{Referenciais teóricos}
% ----------------------------------------------------------
%\input{cap03}
%
% ----------------------------------------------------------
% PARTE DOS RESULTADOS
% ----------------------------------------------------------
%\part{Resultados}
% ----------------------------------------------------------
%\input{cap05}
% ----------------------------------------------------------
% Finaliza a parte no bookmark do PDF
% para que se inicie o bookmark na raiz
% e adiciona espaço de parte no Sumário
% ----------------------------------------------------------
%\phantompart
% ---
% Conclusão (outro exemplo de capítulo sem numeração e presente no sumário)
% ---
%\chapter*[Conclusão]{Conclusão}
%\addcontentsline{toc}{chapter}{Conclusão}
% ---
%\input{cap06}


% ----------------------------------------------------------
% ELEMENTOS PÓS-TEXTUAIS
% ----------------------------------------------------------
\postextual
% ----------------------------------------------------------

% ----------------------------------------------------------
% Referências bibliográficas
% ----------------------------------------------------------
\bibliography{referencias}

% ----------------------------------------------------------
% Glossário
% ----------------------------------------------------------
%
% Consulte o manual da classe abntex2 para orientações sobre o glossário.
%
%\glossary

% ----------------------------------------------------------
% Apêndices
% ----------------------------------------------------------

\begin{apendicesenv}

% Imprime uma página indicando o início dos apêndices
\partapendices

   % Existem várias formas de se colocar anexos.
   % O exemplo abaixo coloca 2 apêndices denominados de 
   % DESENVOLVIMENTO DETALHADO DA PINTURA e 
   % ESCOLHA DO MATERIAL DE IMPRESSÃO:
   % ---
   % --- insere um capítulo que é tratado como um apêndice
   %\chapter{DESENVOLVIMENTO DETALHADO DA PINTURA}
   % 
   %\lipsum[29] % gera um parágrafo
   %
   % --- insere um capítulo que é tratado como um apêndice
   %\chapter{ESCOLHA DO MATERIAL DE IMPRESSÃO}
   % 
   %\lipsum[30] % gera um parágrafo


% --- Insere o texto do arquivo ap01.tex
% 
% --- O conteúdo do arquivo pode ser vários anexos ou um único apêndices.
%     A vantagem de se utilizar este procedimento é de suprimi-lo
%     das compilações enquanto se processa o resto do documento.

\input{ap01}

\end{apendicesenv}
% ---


% ----------------------------------------------------------
% Anexos
% ----------------------------------------------------------

\begin{anexosenv}

% --- Imprime uma página indicando o início dos anexos
 \partanexos

   % Existem várias formas de se colocar anexos.
   % O exemplo abaixo coloca 2 anexos denominados de 
   % TABELA DE VALORES e GRÁFICOS DE BALANCEMANTO:
   % ---
   % --- insere um capítulo que é tratado como um anexo
   %\chapter{TABELAS DE VALORES}
   % 
   %\lipsum[31] % gera um parágrafo
   %
   % --- insere um capítulo que é tratado como um anexo
   %\chapter{GRÁFICOS DE BALANCEAMENTO}
   % 
   %\lipsum[32] % gera um parágrafo


% --- Insere o texto do arquivo ax01.tex
% 
% --- O conteúdo do arquivo pode ser vários anexos ou um único anexo.
%     A vantagem de se utilizar este procedimento é de suprimi-lo
%     das compilações enquanto se processa o resto do documento.

 \input{ax01} 


\end{anexosenv}

%---------------------------------------------------------------------
% INDICE REMISSIVO
%---------------------------------------------------------------------
%\phantompart
%\printindex
%---------------------------------------------------------------------

\end{document}
```