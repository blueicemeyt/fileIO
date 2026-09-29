``` text

Examples:
  stream.cpp
  fileIO.cpp


# Writing a file

std:ofstream outFile;
  // it's called "Outfile" because its the output file

outFile.open("example.dat")
  // attach stream to a file

if (outFile.is_open()){
  // checks is the file exists, then reads data
  outFile << "eggs" << std::endl; 

  else{
  std::cout << "unable to open file" << std::endl;
  // if file does not exist, it is not read

appFile.open("example.dat", std::ios::app);
  // opens the file for appending
  // the default is that if the file is opened and being changes, the og file is deleted and y     you start from scratch


# Reading a file

  // When reading a file, you don't know when it's done
std::ifstream inFile;
inFile.oepn("example.dat");
std::string item;
while (!inFile.eof()){
  // "eof" means end of file
  std::getline(inFile, item);
    std


```
