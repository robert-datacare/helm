## Field Descriptions

### 1.0 Persistent Volume (PV)
- Create and define a persistent storage volume

#### 1.1 PV Name
- Please choose whether to leave the default name or enter a custom name for the persistent volume. This name will be appended to the application name you provided on the previous page. For example, if the application name is "appname" and you enter "pv" here, the persistent volume name would be "pv-appname."

#### 1.2 PV Size
- Please enter the desired size of the persistent volume in gibibytes (GiB) or choose to leave the default size of 20 GiB.

#### 1.3 PV Type
- Please select the type of persistent volume. "ReadWriteMany" indicates that the volume can be shared across multiple deployments, while "ReadWriteOnce" means that the volume is accessible only by a single deployment.

### 2.0 GPU Deployment (DP 1)
- Define your application deployment

#### 2.1 DP 1 Image
- Please select the application you would like to install from the provided list.

#### 2.2 DP 1 Replicas
- Please specify the number of application replicas you would like to run. By default, one instance of the application will be launched.

#### 2.3 DP 1 GPUs
- Please enter the number of GPUs you would like to assign per instance.

#### 2.4 DP 1 PV Mount Point
- You can choose to leave the default mount path for the persistent volume or enter a custom path. The persistent volume will be accessible within the application from the specified path.

#### 2.5 DP 1 Network Name
- Please enter a name, which must be less than 15 characters, that will be used for network services. This name will serve as the beginning of your application URL.

#### 2.6 DP 1 Cluster IP Port
- Please enter the port number that you would like to open in the application.

### 3.0 NON GPU Deployment (DP 2)
- Please select the checkbox if you would like to set up a second application deployment.

#### 3.1 DP 2 Image
- Please select the application you would like to install from the provided list.

#### 3.2 DP 2 Replicas
- Please specify the number of application replicas you would like to run. By default, one instance of the application will be launched.

#### 3.3 DP 2 PV Mount Point
- You can choose to leave the default mount path for the persistent volume or enter a custom path. The persistent volume will be accessible within the application from the specified path.

#### 3.4 DP 2 Network Name
- Please enter a name, which must be less than 15 characters, that will be used for network services. This name will serve as the beginning of your application URL.

#### 3.5 DP 2 Cluster IP Port
- Please enter the port number that you would like to open in the application.
