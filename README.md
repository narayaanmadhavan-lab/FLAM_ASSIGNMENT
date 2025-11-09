\documentclass{article}
\usepackage{amsmath}
\title{FLAM Assignment - Parametric Curve Estimation Results}
\author{Your Name}
\date{\today}

\begin{document}
\maketitle

\section*{Unknown Variables Result}

After optimization, the estimated values of the unknown variables are:

\[
\theta = 28.12^\circ, \quad
M = 0.0214, \quad
X = 54.90
\]

Final L1 Loss: 25.24

\section*{Final Parametric Equations}

The parametric equations with the estimated parameters are:

\[
x = t \cos(28.12^\circ) - e^{0.0214 |t|} \sin(0.3 t) \sin(28.12^\circ) + 54.90
\]

\[
y = 42 + t \sin(28.12^\circ) + e^{0.0214 |t|} \sin(0.3 t) \cos(28.12^\circ)
\]

\end{document}
