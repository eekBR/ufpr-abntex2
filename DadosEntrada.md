
```
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Arquivo para entrada de dados para a parte pré textual
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% 
% Basta digitar as informações indicidas, no formato 
% apresentado.
%
%%%%%%%
% Os dados solicitados são, na ordem:
%
% título do trabalho
% nome do autor
% local 
% data (ano com 4 dígitos)
% orientador
% coorientador
% instituição
% tipo de trabalho
% preambulo
% epígrafe
% resumo
% palavras chave
% abstract
% keywords
% agradecimentos
% dedicatoria
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% ---
% Informações de dados para CAPA e FOLHA DE ROSTO
% ---
\titulo{Modelo de\\ trabalho acadêmico com \abnTeX}
\autor{Seu nome}
\local{Curitiba}
\data{2014} %Apenas ano 4 dígitos
\orientador{Emílio Eiji Kavamura}
\coorientador{Equipe \abnTeX}
\instituicao{%
  Universidade Federal do Paraná
  }
  %\par
  %Departamento de Expressão Gráfica
  %\par
  %Curso de Expressão Gráfica}
\tipotrabalho{Trabalho Acadêmico}
% O preambulo deve conter o tipo do trabalho, o objetivo, 
% o nome da instituição e a área de concentração 
\preambulo{Trabalho apresentado como requisito parcial para a obtenção do grau de Bacharel em Expressão Gráfica no curso de Expressão Gráfica, Setor de Exatas da Universidade Federal do Paraná.}
% ---
\newcommand{
\EpigrafeTexto}{
\textit{``Não vos amoldeis às estruturas deste mundo, \\
		mas transformai-vos pela renovação da mente, \\
		a fim de distinguir qual é a vontade de Deus: \\
		o que é bom, o que Lhe é agradável, o que é perfeito.\\
		(Bíblia Sagrada, Romanos 12, 2)}
}
% ---
\newcommand{
\ResumoTexto}{
Segundo a \citeonline[3.1-3.2]{abntex2modelo}, o resumo deve ressaltar o
  objetivo, o método, os resultados e as conclusões do documento. 
A ordem e a extensão destes itens dependem do tipo de resumo (informativo
ou indicativo) e do tratamento que cada item recebe no documento original. 
O resumo deve ser precedido da referência do documento, com exceção do 
resumo inserido no próprio documento. (\ldots) As palavras-chave devem 
figurar logo abaixo do  resumo, antecedidas da expressão Palavras-chave:, separadas entre si por ponto e finalizadas também por ponto.
}
% ---
\newcommand{
\PalavraschaveTexto}{
latex. abntex. editoração de texto.
}
% ---
\newcommand{
\AbstractTexto}{
This is the english abstract.
}
% ---
\newcommand{
\KeywordsTexto}{
latex. abntex. text editoration.
}
% ---
\newcommand{
\AgradecimentosTexto}{
Os agradecimentos principais são direcionados à Gerald Weber, Miguel Frasson, Leslie H. Watter, Bruno Parente Lima, Flávio de  Vasconcellos Corrêa, Otavio Real Salvador, Renato Machnievscz\footnote{Os nomes dos integrantes do primeiro
projeto abn\TeX\ foram extraídos de \url{http://codigolivre.org.br/projects/abntex/}} e todos aqueles que contribuíram para que a produção de trabalhos acadêmicos conforme as normas ABNT com \LaTeX\ fosse possível.

Agradecimentos especiais são direcionados ao Centro de Pesquisa em Arquitetura da Informação\footnote{\url{http://www.cpai.unb.br/}} da Universidade de Brasília (CPAI), ao grupo de usuários
\emph{latex-br}\footnote{\url{http://groups.google.com/group/latex-br}} e aos novos voluntários do grupo \emph{\abnTeX}\footnote{\url{http://groups.google.com/group/abntex2} e
\url{http://abntex2.googlecode.com/}}~que contribuíram e que ainda
contribuirão para a evolução do \abnTeX.

Os agradecimentos principais são direcionados à Gerald Weber, Miguel Frasson, Leslie H. Watter, Bruno Parente Lima, Flávio de Vasconcellos Corrêa, Otavio Real Salvador, Renato Machnievscz\footnote{Os nomes dos integrantes do primeiro
projeto abn\TeX\ foram extraídos de \url{http://codigolivre.org.br/projects/abntex/}} e todos aqueles que contribuíram para que a produção de trabalhos acadêmicos conforme as normas ABNT com \LaTeX\ fosse possível.
}
% ---
\newcommand{
\DedicatoriaTexto}{
\textit{ Este trabalho é dedicado às crianças adultas que,\\
   quando pequenas, sonharam em se tornar cientistas.}
	}
% ---	
```