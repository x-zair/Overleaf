# Overleaf
Overleaf and its many secrets
\subsection{Title}
unnumberd:
\subsection*{}

For code insertion inside:
\usepackage{minted}


in text:

\begin{minted}{bash}
java -jar ./jvarkit.jar biostar154220 -d <target_depth(int)> -o <output.sam> <input.sam>
\end{minted}


Link insertion:

deposited in \href{https://github.com/x-zair/ONT\_truthset/tree/main/sanger\_plasmids}{study repository}: 
\url{https://github.com/x-zair/ONT\_truthset/tree/main/sanger\_plasmids}).


\footnote{\url{(https://github.com/nanoporetech/dorado}}[v0.5.3)]


comment:

cnt + /

\begin{table}[h]
\centering
\caption{Your caption here}
\label{tab:yourlabel}
\resizebox{\textwidth}{!}{%
\begin{tabular}{column specs}
% table content
\end{tabular}%
}
\end{table}


adding images:

## LaTeX Float Placement Options

| Option | Meaning |
|--------|---------|
| `h` | Here (approximately where written) |
| `t` | Top of page |
| `b` | Bottom of page |
| `p` | Own dedicated page |
| `H` | Exactly here (requires `\usepackage{float}`) |
| `!` | Override LaTeX defaults |

### Examples
```latex
\begin{figure}[H]     % Exactly here
\begin{figure}[p]     % Own page
\begin{figure}[htbp]  % Flexible placement
\begin{figure}[!h]    % Force here
```
