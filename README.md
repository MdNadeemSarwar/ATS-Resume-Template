\documentclass[a4paper,11pt]{article}
\usepackage{latexsym}
\usepackage{xcolor}
\usepackage{float}
\usepackage{ragged2e}
\usepackage[empty]{fullpage}
\usepackage{wrapfig}
\usepackage{lipsum}
\usepackage{tabularx}
\usepackage{titlesec}
\usepackage{geometry}
\usepackage{marvosym}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage{multicol}
\usepackage{graphicx}
\usepackage{cfr-lm}
\usepackage[T1]{fontenc}
\usepackage{fontawesome}
\usepackage[most]{tcolorbox}
\usepackage{indentfirst} % Ensure first line indentation

% Set the margins
\geometry{left=1.5cm, top=1.5cm, right=1.5cm, bottom=1.5cm}
% Define custom colors
\definecolor{myviolet}{RGB}{140, 93, 183} % Define custom violet color
% Set the margins
\geometry{left=0.85cm, top=0.8cm, right=0.85cm, bottom=0.2cm}

% Paragraph indentation setting

\setlength{\parindent}{10pt} % Adjust the indentation value as needed

% Sections formatting with custom color
\titleformat{\section}{
\vspace{-4pt}\color{myviolet}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-7pt}]

%-------------------------
% Custom commands
\newcommand{\resumePOR}[3]{%
\vspace{0.5mm}\item[]
\begin{tabular*}{\textwidth}[t]{l@{\extracolsep{\fill}}r}
\hspace{-3mm}{#1}:\hspace{1mm} & \hspace*{0pt}\hfill{\footnotesize{ #3}} \vspace{-
0.5mm}\\ \hspace{-2.9mm}#2
\end{tabular*}
\vspace{0mm}
}

\newcommand{\resumeExp}[4]{%
\vspace{0mm}\item[]
\begin{tabular*}{\textwidth}[t]{l@{\extracolsep{\fill}}r}
\hspace{-4.4mm} \small\textbf{#1} & {\footnotesize{#3}}\vspace{-1.2mm}\\
\hspace{-4.3mm} \footnotesize{\text{#2}} & \footnotesize{#4}
\end{tabular*}
\vspace{-6.1mm}
}

\newcommand{\resumeProject}[4]{%
\vspace{0mm}\item[]
\begin{tabular*}{\textwidth}[t]{l@{\extracolsep{\fill}}r}
\hspace{-4.4mm} \small\textbf{#1} & {\footnotesize{#3}}\vspace{-1mm}\\
\hspace{-4.3mm} \footnotesize{\text{#2}} & \footnotesize{#4}
\end{tabular*}

\vspace{-6.5mm}
}

\newcommand{\resumeEdu}[4]{%
\vspace{0mm}\item[]
\begin{tabular*}{\textwidth}[t]{l@{\extracolsep{\fill}}r}
\hspace{-4.3mm} \small\textbf{#1} & \footnotesize{#3}\vspace{-1mm} \\
\hspace{-4.3mm} \footnotesize{#2} & \footnotesize{#4}
\end{tabular*}
\vspace{-3.2mm}
}

\newcommand{\resumeAchieve}[3]{%
\hspace{-3.1mm}\textbf{ #1} & {#2} & \hspace{3mm}\footnotesize{#3}
\vspace{0mm}\\
}

\renewcommand{\labelitemi}{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*,labelsep=0mm,ite
msep=-2.5mm]}

\newcommand{\resumeItemListStart}{\begin{justify}\begin{itemize}[leftmargin=3ex,
rightmargin=2ex, noitemsep,labelsep=1.2mm,itemsep=0mm]\small}

\newcommand{\resumeSubHeadingListEnd}{\end{itemize}\vspace{-2mm}}
\newcommand{\resumeItemListEnd}{\end{itemize}\end{justify}\vspace{-1.5mm}}

\renewcommand{\arraystretch}{1}

\newcolumntype{L}{>{\raggedright\arraybackslash}X}%
\newcolumntype{R}{>{\raggedleft\arraybackslash}X}%
\newcolumntype{C}{>{\centering\arraybackslash}X}%

%---- End of Packages and Functions ------

%-------------------------------------------
%%%%%% CV STARTS HERE %%%%%%%%%%%

\newcommand{\name}{Md Nadeem Sarwar}
\newcommand{\address}{Darbhanga, Bihar India}
\vspace{-5.5mm}
\newcommand{\course}{B.Tech - Computer Science and Engineering} % Your Course
\newcommand{\roll}{xxxxxxxx} % Your Roll No.
\newcommand{\phone}{00000000} % Your Phone Number
\newcommand{\emaila}{MdNadeemsarwar12@gmail.com} %Email 1

\begin{document}
\fontfamily{cmr}\selectfont

%----------HEADING-----------------
\begin{center}
\LARGE{\textbf{\name}} \\
\vspace{1mm}
\small{\text{\address}}
\end{center}
\vspace{-5.5mm}

\begin{center}
\small{\href{https://github.com/MdnadeemSarwar}{\faGithub \hspace{0.2mm} github} |
\href{https://www.linkedin.com/in/md-nadeem-sarwar/}{\faLinkedinSquare \hspace{0.2mm}
linkedin} | \href{mailto:sarwar1@gmail.com}{\faSend \hspace{0.2mm}sarwar1@gmail.com} |
\faPhone \hspace{0.2mm} +91-00000000} |
{\href{https://leetcode.com/u/MdNadeemSarwar/}{LeetCode} |
{\href{https://www.youtube.com/@Soft-Server}{YT-Channel}
\end{center}
\vspace{-3mm}

%-----------EDUCATION-----------------

\vspace{-4.5mm}
\section{Education}

\resumeSubHeadingListStart
\resumeEdu
{Galgotias University}
{Bachelors of Technology in Computer Science and Engineering}
{Nov 2020 - May 2024} %Event Dates
{\textbf{CGPA: 8.6/10}} %Website
\vspace{2.5mm}

% \resumeSubHeadingListStart

\resumeEdu
{Chandradhari Mithila Science College}
{Senior Secondary (Class XII)}
{Apr 2018 - Mar 2020} %Event Dates
{\textbf{Percentage: 73.8}} %Website

\resumeSubHeadingListEnd
\vspace{-4.5mm}

%-----------EXPERIENCE-----------------
\section{Experience}
\resumeSubHeadingListStart
\vspace{-0.5mm}
\resumeExp
{\href{https://mvp.microsoft.com/en-US/studentambassadors/profile/820fbb1f-de55-4d22-
971f-580d08f0bada}{\textbf{Microsoft Learn Student Ambassador | Microsoft}}}

{April 2024 - Till date}
{}
\vspace{-3mm}
\resumeItemListStart
\item[$\bullet$] Representing Microsoft's educational initiatives and technology resources to
students and educators
\item[$\bullet$] Organized and led workshops, webinars, and events to promote Microsoft
Learn's educational content and tools, empowering fellow students to enhance their
technical skills.

\item[$\bullet$] Conducted az-900 training as a certified student trainer and organized
various technical events with 500+ attendees from all around the world.
\resumeItemListEnd
\vspace{-1mm}
\resumeExp
% {{\textbf{Salesforce Developer | Intern | Salesforce }}}
{\href{https://www.salesforce.com/trailblazer/heb7l0j5v15zcaxv08}{\textbf{Salesforce
Developer | Intern | Salesforce}}}

{Jan 2024 - Mar 2024} %Event Dates
{}

\vspace{-3mm}

\resumeItemListStart
\item[$\bullet$]Developed custom applications on the Salesforce platform using Apex code
and Visualforce.
\item[$\bullet$]Contributed to enhancing functionality and user experience through the
creation of tailored solutions.
\item[$\bullet$]Gained valuable hands-on experience in building applications to meet specific
business requirements within the Salesforce ecosystem.
\resumeItemListEnd

\vspace{-1mm}

% \vspace{1.0mm}
\resumeExp
{\href{}{\textbf{Full Stack developer | Seoteq Services Pvt Ltd}}}

{Aug 2023 - Nov 2023} %Event Dates
{}

\vspace{-3mm}

\resumeItemListStart
\item[$\bullet$]Worked on the Seoteq team, contributing to the planning, design, and
development of full-stack web applications.
\item[$\bullet$]Implemented front-end components with Backbone.js, Java, Stylus, and
Require JS. Contributed to back-end development using Node js with React framework.

\resumeItemListEnd

% \vspace{1.0mm}

\resumeExp
{\href{}{\textbf{Business Development Associate | Max IT Consulting LLC}}}

{May 2023 - Jun 2023} %Event Dates
{}

\vspace{-3mm}
\resumeItemListStart
\item[$\bullet$]This is a USA-based IT staffing company where We provide them candidates
that have expertise in fields like Developer, Accountant, Designer, Engineer, Manager,
Analyst, and any job field related to the IT industry.
\item[$\bullet$]We check their resumes, visa type, passport, and everything that is necessary
before onboarding them.

\resumeItemListEnd

\resumeItemListEnd

\vspace{-9.0mm}

%-----------PROJECTS-----------------
\section{Projects}
\resumeSubHeadingListStart

\resumeProject
{\href{https://github.com/MdNadeemSarwar/Face-Recognition-Attendance-System}{Face
Recognition Attendance System}}
{}
{\textbf{}}

\vspace{-3mm}
\resumeItemListStart
\item[$\bullet$] LBPH algorithm-based project to manage attendance using facial recognition
with a dataset of 100 images.
\item[$\bullet$] Developed software to register attendance by scanning faces and providing
user information.
\item[$\bullet$] Implemented efficient database storage for managing student and login
authentication data.
\resumeItemListEnd

\vspace{1mm}

\resumeProject
{\href{https://nadeemsarwar.netlify.app/}{Portfolio Personal Web Project}}
{}
{\textbf{}}

\vspace{-3mm}

\resumeItemListStart
\item[$\bullet$] Personal portfolio website showcasing skills, projects, and achievements
using HTML, CSS, and JavaScript..
\item[$\bullet$] Designed and developed a visually appealing website deployed on GitHub
Pages.
\item[$\bullet$] Managed project files using version control for collaboration and tracking
changes.
\resumeItemListEnd

\resumeSubHeadingListEnd

\vspace{-8mm}

\section{Certifications}
\resumeItemListStart

\item[$\bullet$]\textbf{\href{https://drive.google.com/file/d/18xr6Rh_uhQ1vg-
oAzmTKUX4Ldzoyb9Cs/view?usp=sharing}{Oracle}} Database Designing

% \vspace{-0.5mm}
\item[$\bullet$]\textbf{\href{https://drive.google.com/file/d/16lCfwtfQ7pvjVgqN4jzM1qCd1cnz
Av7Q/view}{Infosys Springboard}} (Database Management System)
% \vspace{-0.5mm}

\item[$\bullet$]\textbf{\href{https://www.credly.com/users/md-nadeem-sarwar/badges}{AWS-
Amazon}} Web Services (Clouds and Machine Foundations)

% \vspace{-0.5mm}
\item[$\bullet$]\textbf{\href{https://drive.google.com/file/d/1xWQWPZRAibXQD_YXBWZhTfS
HNUd63Hb8/view}{Cisco}} Certified Associate Python Programmer by \textbf{OpenEDG}.
% \vspace{-0.5mm}
\item[$\bullet$]\textbf{\href{https://drive.google.com/file/d/1n9nMzeshaQQR3Y2VxvrNrBhZX
usJQyjo/view}{Ministry of Electronics and Information Technology}}(Cyber Security)
% \vspace{-0.5mm}

\item[$\bullet$]\textbf{\href{https://www.linkedin.com/posts/md-nadeem-sarwar_coding-
experience-problemsolving-activity-7070820397344002048-

v0AB?utm_source=share&utm_medium=member_desktop}{Coding Ninjas}} Successfully
Clearing the Day -1 Program \textbf{Technical Round}.
% \vspace{-0.5mm}

\item[$\bullet$]\textbf{\href{https://drive.google.com/file/d/15ejbUAvFwOO0AoNipcX48CmLui
uTP4JU/view?usp=sharing}{IIC Galgotias University}}(Participate in Innovative Approaches
for Energy Conservation)
\resumeItemListEnd

\vspace{-7.0mm}

% \begin{document}

%-----------SKILLS AND INTERESTS-----------------
\section{Skills and Interests}
\begin{flushleft}
C++, Java, Python, HTML, CSS, JavaScript, React.js, Node.js, MongoDB, Firebase, SQL,
Git, SEO Optimization, Microsoft 360 Tools, Video Editing, Logo Designing, Content
Creation, Teamwork, Leadership, Public Speaking
\end{flushleft}

\vspace{-9mm}

%-----------RELEVANT COURSEWORK-----------------
\section{Relevant Coursework}
\begin{flushleft}
Data Structures, Algorithm, Database Management System, Object Oriented
Programming, MySQL, Machine Learning, Artificial Intelligence, Natural Language
Processing, UI Design
\end{flushleft}

\vspace{-9mm}

%-----------POSITIONS OF RESPONSIBILITY-----------------
\section{Positions of Responsibility}
\noindent % Remove paragraph indentation
\textbf{Head of E-Cell Club Team at Galgotias University} \\
Organized events to promote entrepreneurship, facilitated patenting of student ideas, and
guided trademark registration for ventures.

\vspace{-5mm}

%-----------OPEN SOURCE CONTRIBUTION-----------------
\section{Open Source Contribution}
\resumeItemListStart

% Contributed over \textbf{200+ LeetCode solutions} on \textbf{GitHub} to share knowledge
and insights with the community.
% I contribute 50+ to Microsoft's Technical Onboarding on GitHub, providing insights and
knowledge to the community.
\item [$\bullet$]Contributed over \textbf{200+ LeetCode solutions} on \textbf{GitHub} to share
knowledge and insights with the community.
\item[$\bullet$]Contribute 50+to \textbf{MLSA} Technical Onboarding on \textbf{GitHub}
providing insights and knowledge to the community.

\resumeSubHeadingListEnd

\end{document}
