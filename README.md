USE [master]
GO

CREATE DATABASE [demoCRUD]
GO

USE [demoCRUD]
GO


CREATE TABLE [dbo].[Student](
	[StudentNo] [int] NOT NULL PRIMARY KEY,
	[Name] [varchar](50) NOT NULL,
	[Section] [int] NOT NULL,
	[Branch] [varchar](50) NOT NULL,
	[Emailid] [varchar](50) NOT NULL
 )

GO
