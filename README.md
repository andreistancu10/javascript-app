Simple Javascript application that uses mongo database. I used kubernetes cluster that run pods for every app component:

1. Javascript app uses custom image build with azure devops and pull it from azure container registry
2. Mongodb for database
3. Mongoexpress - used for UI database