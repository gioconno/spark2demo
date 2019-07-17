# spark2demo

## Configuration

- Install [Scala with IntelliJ](https://www.scala-lang.org/)

### Windows only
1. Download [winutils.exe](https://github.com/steveloughran/winutils)
2. Copy it in a path similar to `<base_dir>\hadoop\bin`
3. Edit system enviroment variables adding `HADOOP_HOME = <base_dir>\hadoop`
4. In system enviroment variables edit PATH adding `%HADOOP_HOME%\bin`
5. Check if correct by opening a cmd end running the command `winutils.exe`

## Dataset
- You can find the datasets in the project path `src/main/resources/data-master.zip`
- The dataset is also provided by https://github.com/dgadiraju/data
- Copy/download it to the filesystem and unzip it
