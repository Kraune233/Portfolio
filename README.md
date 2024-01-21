#include <GameDemo>
#include <DigitalArtDemo>
#include <WritingSample>
using namespace std;

int main() {
    Work file1; // 
    double information;
    cout << information.get() << endl;
    return 0;
}

clas Work
{
   public fileName;
   public filePath;
};

double Work::get(void)
{
  return fileName + filePath;
}
