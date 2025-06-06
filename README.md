# RLD 
\begin{table}[t]
\centering
\setlength{\tabcolsep}{4pt} % 将列间距减小到 3pt
\begin{tabular}{lccccc}
\toprule
Method & Params (M) & FLOPs (G) & Val mIoU (\%) \\
\hline
T: DeepLabv3-Res101 & 61.1M & 2371.7G & 78.07 \\
\hline
S: DeepLabv3-Res18 & 13.6M &  & 74.21  \\
% +DSD  & 13.6M  & & 74.37  \\
+SKD \cite{liu2019structured} (CVPR'19) & 13.6M  & & 75.42  \\
+IFVD \cite{wang2020intra} (ECCV'20) & 13.6M  &  & 75.64 \\
+CWD \cite{shu2021channel} (ICCV'21)  & 13.6M&  & 76.04  \\
+CIRKD \cite{yang2022cross} (CVPR'22)  & 13.6M &  & 76.38  \\
+MasKD \cite{huang2023masked} (ICLR'23) & 13.6M &572.0G &77.00 \\
+CAD/LAD \cite{liu2024rethinking} (WACV'24) & 13.6M & &76.81 / 76.78 \\
+RDD \cite{RDD} (SCIS'24) & 13.6M & & 77.18 \\
+TD \cite{wu2025td} (PR'25)  & 13.6M & &76.57 \\
+DIST/DIST+ \cite{dist} (TPAMI'25) & 13.6M & & 77.10 / 77.36 \\
\rowcolor{gray!30}
+RLD (Ours) & 13.6M & & \textbf{77.80}  \\
\hline
S: DeepLabv3-MBV2 & 3.2M &  & 73.12 \\
+SKD \cite{liu2019structured} (CVPR'19) & 3.2M   & & 73.82 \\
+IFVD \cite{wang2020intra} (ECCV'20) & 3.2M &   & 73.50  \\
+CWD \cite{shu2021channel} (ICCV'21)& 3.2M & &74.66 \\
+CIRKD \cite{yang2022cross} (CVPR'22)&  3.2M  & 128.9G & 75.42 \\
+MasKD \cite{huang2023masked} (ICLR'23)&  3.2M  &  & 75.26 \\
+RDD \cite{liu2024rethinking} (SCIS'24) & 3.2M & & \textbf{76.38} \\
+TD \cite{wu2025td} (PR'25) & 3.2M & & 75.14 \\
\rowcolor{gray!30}
+RLD (Ours)  &  3.2M  &  & 76.30 \\
\hline
S: PSPNet-Res18 & 12.9M & & 72.55 \\
+SKD \cite{liu2019structured} (CVPR'19)& 12.9M &   & 73.29\\
+IFVD \cite{wang2020intra} (ECCV'20)& 12.9M &  & 73.71\\
+CWD \cite{shu2021channel} (ICCV'21)& 12.9M  &  & 74.36\\
+CIRKD \cite{yang2022cross} (CVPR'22)& 12.9M & 507.4G & 74.73 \\
+MasKD \cite{huang2023masked} (ICLR'23)& 12.9M &  & 75.34 \\
+RDD \cite{RDD} (SCIS'24)& 12.9M &  & 75.88 \\
+TD \cite{wu2025td} (PR'25)& 12.9M &  &  76.24 \\
+DIST/DIST+ \cite{wu2025td} (TPAMI'25)& 12.9M &  &  76.31 / 76.52 \\
\rowcolor{gray!30}
+RLD (ours) & 12.9M &  &  \textbf{76.55} \\
\bottomrule
\end{tabular}
