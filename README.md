# Remote-Build-Server
Developed a Build Server for the automation of Building and testing C# files that accepts a build request ( an XML file with a set of
test cases and a test driver for those test cases), parse the accepted XML, get the required files specified in the XML file, Build
Dynamic Link Libraries for each test in the XML(Build Request) and Test them and publish the results to the user.

Integrated the above-mentioned Core Build Server into a system which has a federation of standalone servers implementing the Process Pool mechanism where we the client can choose the number of builder processes to be run in parallel and build multiple build requests thus increasing the efficiency of the automation process. We can access the Build server from any internet enabled processor
