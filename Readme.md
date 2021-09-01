#FolderSize

File system tree traversal program:

	-After launch, you need to enter the absolute path to the processed folder in the console and press ENTER
	-The bypass logic is implemented in the FileUtils class
	-To display messages from the program, the Logger of the log4j library is used
	-Message templates are declared in enum MsgTemplates
	-If the specified path does not lead to a folder, a FileFormatException is thrown


Программа обхода дерева файловой системы:

	-После запуска требуестся ввести в консоль абсолютный путь до обрабатываемой папки и нажмите ENTER
	-Логика обхода реализована в классе FileUtils
	-Для вывода сообщений от программы используется Logger библиотеки log4j
	-Шаблоны сообщений обьявлены в enum MsgTemplates
	-В случае если указанный путь ведет не к папке выбрасывается FileFormatException   
