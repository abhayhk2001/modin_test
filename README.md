Pandas worked fine with 2 sec.

Modin[all] installation gives error ->

after error : pip freeze
numpy==1.23.4
pandas==1.5.1
python-dateutil==2.8.2
pytz==2022.6
six==1.16.0


Installing modin only -> No error
pip freeze : 
fsspec==2022.10.0
modin==0.16.2
numpy==1.23.4
packaging==21.3       
pandas==1.5.1
psutil==5.9.4
pyparsing==3.0.9      
python-dateutil==2.8.2
pytz==2022.6
six==1.16.0


installing modin with dask only: modin[dask] -> no error
pip freeze : 

click==8.1.3
cloudpickle==2.2.0
colorama==0.4.6
dask==2022.10.2
distributed==2022.10.2
fsspec==2022.10.0
HeapDict==1.0.1
Jinja2==3.1.2
locket==1.0.0
MarkupSafe==2.1.1
modin==0.16.2
msgpack==1.0.4
numpy==1.23.4
packaging==21.3
pandas==1.5.1
partd==1.3.0
psutil==5.9.4
pyparsing==3.0.9
python-dateutil==2.8.2
pytz==2022.6
PyYAML==6.0
six==1.16.0
sortedcontainers==2.4.0
tblib==1.7.0
toolz==0.12.0
tornado==6.1
urllib3==1.26.12
zict==2.2.0


But running program is going haywire - 
log in daskrun1.log