## latex beamer presentation template

# Usage

Put it in the same directory as your presentation and source it using the `\usetheme` command.

# Example

```
\documentclass{beamer}
\usepackage[utf8]{inputenc}
\usetheme{pmos}

\title{PostmarketOS}
\subtitle{10 year lifecycle for smartphones}
\author{John Doe}
\date{\today}

\begin{document}

\frame{\titlepage}

\begin{frame}{Title}
\begin{itemize}
	\item<1->Item 1
	\item<2->Item 2
	\item<3->Item 3
	\item<4->Item 4
\end{itemize}
\end{frame}

\end{document}
```

![](https://i.imgur.com/QAZ0BUQ.png)
![](https://i.imgur.com/QpeTfz5.png)
