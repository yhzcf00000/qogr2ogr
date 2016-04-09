This tool is based ogr2ogr which is a utility program in GDAL.

Qogr2ogr is a GUI and multi-thread application.It make easy to convert geospatial data to another format or save to database.It provides 4 way to work:File->File, File->Database, Database->File, Database->Database.Although it is now not perfect, it will bring you advantage for processing geospatial data.

Qogr2ogr是一个基于ogr2ogr的GUI工具,ogr2ogr是一个GDAL中包含的实用程序。
Qogr2ogr是GUI界面和多线程的程序，用以互相转换空间数据或储存到数据库中。Qogr2ogr提供了4种数据转化的途径：文件->文件、文件->数据库、数据库->文件、数据库->数据库。它虽然还不完善，但相信它会为你处理空间数据带来便利。

Qogr2ogr supports these formats now/当前Qogr2ogr支持如下格式：

---Data Source
> --File
> > ESRI Shapefile(.shp)
> > MapInfo File(.tab)
> > GML(.gml)
> > KML(.kml)
> > Arc/Info Binary Coverages(.e00)
> > Atlas BNA(.bna)
> > CSV(.csv)
> > Microstation DGN(.dgn)
> > SDTS(.ddf)
> > Interlis 1(.itf)
> > Interlis 2(.xml)
> > GMT(.gmt)
> > GPX(.gpx)
> > UK.NTF(.ntf)

> --Database
> > PostgreSQL
> > MySQL
> > ODBC(no test, may not work)

---Output Data

> --File
> > ESRI Shapefile(.shp)
> > MapInfo File(.tab)
> > GML(.gml)
> > KML(.kml)
> > CSV(.csv)
> > Microstation DGN(.dgn)
> > Interlis 1(.itf)
> > Interlis 2(.xml)

> --Database
> > PostgreSQL
> > MySQL
> > ODBC(no test, may not work)