# essential_macros_for_data_science
I used Keyboard Maestro to create shortcuts for essential data science functions. Parameters to all functions are provided as fill-in-the-blanks. Macros and macro triggers can be edited using the Keyboard Maestro desktop app.

Visit https://www.keyboardmaestro.com/main/ to download compatible software for running macros.

Git Macros:

	Trigger		Macro
		
	;gita		Git – git add
	;gitc		Git – git commit -m '
	;gitpush	Git – git push -u origin master
	;gitrem		Git – git remote add origin
	;mga		Git – more .gitattributes
	;gitrm		Git – Remove Local Git Repository
	;git0h		Git – Undo Commits - reset HEAD~
	;lflk		Git Lfs – git lfs ls-files
	;lfmigall	Git Lfs – git lfs migrate import --everything --
	;lft		Git Lfs – git lfs track '*.' - File Extension
	;lfut		Git Lfs – git lfs untrack '

Matplotlib & Seaborn Macros:

	Trigger		Macro
		
	;mplaxt		Matplotlib – axes.set_title('')
	;mplaxx		Matplotlib – axes.set_xlabel('')
	;mplaxy		Matplotlib – axes.set_ylabel('')
	;mplfa		Matplotlib – fix, axes
	;mplfig		Matplotlib – plt.figure
	;mpsub		Matplotlib – plt.subplot(, , )
	;mplt		Matplotlib – plt.title('')
	;mplx		Matplotlib – plt.xlabel('')
	;mply		Matplotlib – plt.ylabel('')
	;snsbar		Seaborn – sns.barplot
	;snsbox		Seaborn – sns.boxplot
	;snscount	Seaborn – sns.countplot
	;snsdspine	Seaborn – sns.despine()
	;snsdist	Seaborn – sns.distplot
	;snsheat	Seaborn – sns.heatmap
	;snscheat	Seaborn – sns.heatmap – df.corr
	;snsjointg	Seaborn – sns.jointgrid
	;snsjointp	Seaborn – sns.jointplot
	;snskde		Seaborn – sns.kdeplot
	;snslm		Seaborn – sns.lmplot
	;snspp		Seaborn – sns.pairplot
	;snsstrip	Seaborn – sns.stripplot
	;snsswarm	Seaborn – sns.swarmplot
	;snsviolin	Seaborn – sns.violinplot

Pandas & Numpy Macros:

	Trigger		Macro
		
	;argmax		Numpy  – .argmax()
	;argmin		Numpy  – .argmin()
	;copy		Numpy  – .copy()
	;max		Numpy  – .max()
	;mean		Numpy  – .mean()
	;min		Numpy  – .min()
	;sum		Numpy  – .sum()
	;npreshape	Numpy – arr.reshape()
	;npra		Numpy – np.arange(, )
	;nparr		Numpy – np.array()
	;exp		Numpy – np.exp()
	;npi		Numpy – np.eye()
	;nplin		Numpy – np.linspace((, , ))
	;log		Numpy – np.log()
	;np1		Numpy – np.ones((, ))
	;nprand		Numpy – np.random.rand()
	;npintrand	Numpy – np.random.randint()
	;npnrand	Numpy – np.random.randn()
	;sin		Numpy – np.sin()
	;sqrt		Numpy – np.sqrt()
	;np0		Numpy – np.zeros((, ))
	;pdh		Pandas – .head()
	;pdin		Pandas – .isnull()
	;vc		Pandas – .value_counts()
	;dfarea		Pandas – df.area
	;pdfloat	Pandas – df.astype(float)
	;pdint		Pandas – df.astype(int)
	;pdstr		Pandas – df.astype(str)
	;dfbar		Pandas – df.bar
	;dfbox		Pandas – df.box
	;pacon		Pandas – df.concat
	;dfdrop		Pandas – df.drop
	;dfgby		Pandas – df.groupby
	;dfagggby	Pandas – df.groupby().agg(aggregations)
	;dfinname	Pandas – df.index.name
	;dfline		Pandas – df.line
	;dfrename	Pandas – df.rename
	;dfreplace	Pandas – df.replace
	;dfscat		Pandas – df.scatter
	;df2scat	Pandas – df.scatter - Joint Axis
	;dfmatscat	Pandas – df.scatter_matrix
	;dfsetax	Pandas – df.set_axis
	;dfsort		Pandas – df.sort
	;pdagg		Pandas – pd.agg
	;pddf		Pandas – pd.df
	;pdrcsv		Pandas – pd.read_csv
	;pddate		Pandas – pd.to_datetime

Plotly & Cufflinks Macros:

	Trigger			Macro
		
	go.scatline		Plotly & Cufflinks – go.scatter Line Plot
	go.scatmline		Plotly & Cufflinks – go.scatter Lines + Markers Plot
	go.scatmark		Plotly & Cufflinks – go.scatter Marker
	go.scatcmark		Plotly & Cufflinks – go.scatter Marker with Color Scale
	;importpc		Plotly & Cufflinks – Import Libraries - Offline
	;iplot3d		Plotly & Cufflinks – iPlot - 3D Surface
	;iplotbar		Plotly & Cufflinks – iPlot - Bar
	;iplotbox		Plotly & Cufflinks – iPlot - Box
	;iplotbub		Plotly & Cufflinks – iPlot - Bubble
	;iplotheat		Plotly & Cufflinks – iPlot - Heatmap
	;iplothist		Plotly & Cufflinks – iPlot - Histogram
	;iplotscat		Plotly & Cufflinks – iPlot - Scatter
	;iplotspread		Plotly & Cufflinks – iPlot - Spread

Python (General) Macros:

	Trigger		Macro
		
	;importvis	Python – Import Standard Visualiation Libraries
	;pdoc		Python – pydoc
	;py		Python – python3.6
	;ipy		Python Application – ipython
	;jn		Python Application – jupyter notebook
	;nt		Python Application – nosetests
	;pyscaf		Python Application – pyscaffolding
	;definit	Python Function – def __init__(self):
	;pr		Python Function – Print
	;pltdt		Python Module – Adspy Shared Utilities - plot_decision_tree
	;;x		Python Module – exit()

Sci-Kit Learn Macros:

	Trigger		Macro
		
	;sykm		Sci-Kit Learn – Cluster - KMeans
	;syrf		Sci-Kit Learn – Ensemble - Random Forest
	;importsy	Sci-Kit Learn – Import Libraries
	;sylr		Sci-Kit Learn – Linear Model - Linear Regression
	;sylg		Sci-Kit Learn – Linear Model - Logistic Regression
	;syrg		Sci-Kit Learn – Linear Model - Ridge Regression
	;syoprr		Sci-Kit Learn – Linear Model - Ridge Regression - Optimization - alpha
	;sycr		Sci-Kit Learn – Metrics - Classification Report
	;sygcr		Sci-Kit Learn – Metrics - Classification Report - Post-Grid Search
	;syms		Sci-Kit Learn – Metrics - Model Scores
	;sygs		Sci-Kit Learn – Model Selection - Grid Search CV
	;syopknn	Sci-Kit Learn – Neighbors - KNeighbors - Optimization - n_neighbors
	;syknn		Sci-Kit Learn – Neighbors - KNeighborsClassifier
	;symsc		Sci-Kit Learn – Preprocessing - MinMax Scaler
	;sypf		Sci-Kit Learn – Preprocessing - Polynomial Features
	;syqt		Sci-Kit Learn – Preprocessing - Quantile Transformer
	;syrsc		Sci-Kit Learn – Preprocessing - Robust Scaler
	;syssc		Sci-Kit Learn – Preprocessing - Standard Scaler
	;sysvc		Sci-Kit Learn – SVM - C-Support Vector Classification
	;sytts		Sci-Kit Learn – Train Test Split
	;sydt		Sci-Kit Learn – Tree - Decision Tree
	;syopdt		Sci-Kit Learn – Tree - Decision Tree - Optimization - max_depth

Scrapy Macros:

	Trigger		Macro
		
	;scsh		Scrapy – scrapy shell
	;scsp		Scrapy – scrapy startproject
	;scex		Scrapy – Xpath - .extract()
	;sc@		Scrapy – Xpath - /@href
	;sct		Scrapy – Xpath - /text()
	;scrx		Scrapy – Xpath - resonse.xpath('

Terminal Macros:

	Trigger		Macro
		
	;cl		Terminal – Clear
	;echo		Terminal – Echo Text to File
	;znano		Terminal – Edit Oh My Zsh Nano File
	;find		Terminal – Find File
	;;n		Terminal – nano
	;pipin		Terminal – Pip Install Package
	;pipuser	Terminal – Pip Install User Package
	;pipcurr	Terminal – Pip Reinstall Current Version
	;;q		Terminal – quit()

Text Macros:

	Trigger		Macro
		
	⌘W		Text – Commenting - Highlight –> Comment
	⌥X		Text – Cut Line of Text
	F19		Text – End ) Go to Next Line
	;;i		Text – File Extension - .ipynb
	;;p		Text – File Extension - .py
	;;t		Text – File Extension - .txt
	;ut		Text – utf-8 strict

Virtualenvwrapper Macros:

	Trigger		Macro
		
	;av		Virtualenvwrapper – Activate Virtual Environment
	;virw		Virtualenvwrapper – cd workon_home
	;vircd		Virtualenvwrapper – cdvirtualenv
	;da		Virtualenvwrapper – Deactivate Virtual Environment
	;mkvir		Virtualenvwrapper – mkvirtualenv
	;virset		Virtualenvwrapper – setvirtualenvproject
