`DECLARE @monthID varchar(10) = '2021-04-05'`

`SELECT FORMAT(CONVERT(datetime, @monthID), 'yyyy-MM', 'en-US')  -- 2021-04`
