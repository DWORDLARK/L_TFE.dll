----------------------------------------------------------------------------------------
	L_TFE.DLL
----------------------------------------------------------------------------------------
Driver exports functions: 


 Get_Title_From_Process_Name(procName: ShortString): ShortString;

	Get program Title text from Process name (*.exe)

		Input: Process Name (ShortString)

		Returns: Title (ShortString)



 Get_Title_From_PID(PID: Integer): ShortString;

	Get program Title text from Process ID

		Input: Process ID (Integer)

		Returns: Title (ShortString)



 Get_PID_From_Process_Name(procName: ShortString): integer;

	Get Process ID from process name (*.exe)

		Input: Process Name (ShortString)

		Returns: Process ID (Integer)



 Get_File_Path_From_PID(PID: integer): ShortString;

	Get file full path from Process ID

		Input: Process ID (Integer)

		Returns: File path (ShortString)



 Get_Process_Name_From_PID(PID: integer): ShortString;

	Get process name (*.exe) from Process ID

		Input: Process ID (Integer)

		Returns: Process Name (ShortString)


----------------------------------------------------------------------------------------

	Note:	Not every process has Title !
		



----------------------------------------------------------------------------------------
	Errors:
----------------------------------------------------------------------------------------

	_ERROR_1   process does not exist
	_ERROR_2   empty title
	_ERROR_3   empty process name or process does not exist
	_ERROR_4   Input PID value error


----------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------
v1.0  (14.05.2024)
----------------------------------------------------------------------------------------






----------------------------------------------------------------------------------------
Library created by LARK_1
----------------------------------------------------------------------------------------
