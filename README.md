## **REPOSITORIO DA VÁRIAVEL PS1**

* INTRODUÇÃO

Repositório para armenzamento das PS1 de usuário comum e do usuário root

* UTILIZAÇÃO

<p> Adicionar linha seguinte linha no arquivo ~/.bashrc</p>
*PS1="conteudo_da_PS1"*

[PS1]

---
* MAPA DE OPÇÕES
 \a : an ASCII bell character (07)
 \d : the date in “Weekday Month Date” format (e.g., “Tue May 26”)
 \D{format} : the format is passed to strftime(3) and the result is inserted into the prompt string; an empty format results in a locale-specific time representation. The braces are required
 \e : an ASCII escape character (033)
 \h : the hostname up to the first ‘.’
 \H : the hostname
 \j : the number of jobs currently managed by the shell
 \l : the basename of the shellâ€™s terminal device name
 \n : newline
 \r : carriage return
 \s : the name of the shell, the basename of $0 (the portion following the final slash)
 \t : the current time in 24-hour HH:MM:SS format
 \T : the current time in 12-hour HH:MM:SS format
 \@ : the current time in 12-hour am/pm format
 \A : the current time in 24-hour HH:MM format
 \u : the username of the current user
 \v : the version of bash (e.g., 2.00)
 \V : the release of bash, version + patch level (e.g., 2.00.0)
 \w : the current working directory, with $HOME abbreviated with a tilde
 \W : the basename of the current working directory, with $HOME abbreviated with a tilde
 \! : the history number of this command
 \# : the command number of this command
 \$ : if the effective UID is 0, a #, otherwise a $
 \nnn : the character corresponding to the octal number nnn
 \\ : a backslash
 \[ : begin a sequence of non-printing characters, which could be used to embed a terminal control sequence into the prompt
 \] : end a sequence of non-printing characters

* MAPA DE CORES E OPÇÕES
*Formato:* \[\e[0;30;40m\]
		  	    |  |  |» Número da Cor de Background
                |  |» Número da Cor do Foreground
                |» Formato do Texto 

`Formato do Texto`
> Normal Text		0
> Bold				1	
> Dim				2
> Underline Text	4
> Blink				5
> Reverse			7 (Inverte cor de Foreground e de Background)
> Hidden			8 

`Cores de Foreground`
> Black       	 30     
> Red         	 31     
> Green       	 32     
> Brown       	 33     
> Blue        	 34     
> Purple      	 35     
> Cyan        	 36     
> Light Gray  	 37     
> Dark Gray	  	 90
> Light Red   	 91
> Light Green 	 92
> Light Yellow 	 93
> Light Blue 	 94
> Light Purple 	 95
> Light Cyan	 96
> White			 97

`Cores de Background`
> Black			 40
> Red			 41
> Green			 42
> Brown			 43
> Blue			 44
> Purple		 45
> Cyan			 46
> Light Gray  	 47     
> Dark Gray	  	 100
> Light Red   	 101
> Light Green 	 102
> Light Yellow 	 103
> Light Blue 	 104
> Light Purple 	 105
> Light Cyan	 106
> White			 107
