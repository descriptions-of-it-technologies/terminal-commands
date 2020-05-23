# Terminal Commands.





## Contents at a Glance.
* [About.](#about)
* [Documentation.](#documentation)
* [General.](#general)
* [Ports.](#ports)
* [Process Management.](#process-management)
* [Navigation.](#navigation)
* [File Management.](#file-management)
* [Directory Management.](#directory-management)
* [curl](#curl)
* [Permission.](#permission)
* [Iptables Management.](#iptables-management)
* [Ip6tables Management.](#ip6tables-management)
* [Search.](#search)
* [System and Service Managements.](#system-and-service-managements)
* [Log Managements.](#log-managements)
* [Group Managements.](#groups-managements)
* [Alias.](#alias)
* [Alias for Kubernetes.](#alias-for-kubernetes)
* [Alias for Kubernetes Node.](#alias-for-kubernetes-node)
* [Alias for Kubernetes Deployment.](#alias-for-kubernetes-deployment)
* [Alias for Kubernetes ReplicaSet.](#alias-for-kubernetes-replicaset)
* [Alias for Kubernetes Pod.](#alias-for-kubernetes-pod)
* [Alias for Kubernetes Namespace.](#alias-for-kubernetes-namespace)
* [Alias for Kubernetes Service.](#alias-for-kubernetes-service)
* [Alias for Kubernetes Configmap.](#alias-for-kubernetes-configmap)
* [Alias for Kubernetes Logs.](#alias-for-kubernetes-logs)
* [Alias for Kubernetes Secret.](#alias-for-kubernetes-secret)
* [Alias for Kubernetes PersistentVolumeClaim.](#alias-for-kubernetes-persistentvolumeclaim)
* [Alias for Kubernetes Ingress.](#alias-for-kubernetes-ingress)
* [Alias for Kubernetes Statefulset.](#alias-for-kubernetes-statefulset)
* [Alias for Kubernetes Config.](#alias-for-kubernetes-config)
* [Alias for Kubernetes Port Forwarding.](#alias-for-kubernetes-port-forwarding)
* [Alias for Kubernetes Rollout.](#alias-for-kubernetes-rollout)
* [Git Commands.](https://github.com/Programming-Training-And-Practice/git-main-information/blob/master/git-commands.md)
* [Maven Commands.](https://github.com/Programming-Training-And-Practice/maven-main-information/blob/master/maven-commands.md)
* [Kubernetes Commands.](https://github.com/Programming-Training-And-Practice/kubernetes-main-information/blob/master/kubernetes-commands.md)
* [Articles.](#articles)
* [Conferences.](#conferences)
* [Conference Speakers.](#conference-speakers)
* [Help.](#help)





## About.





## Documentation.
* [Ubuntu Manual.](http://manpages.ubuntu.com/)
* [systemctl](http://manpages.ubuntu.com/manpages/bionic/en/man1/systemctl.1.html)





## Sort this commands.

| Key/Command                             | Description                                                                |
| --------------------------------------- | -------------------------------------------------------------------------- |
| sed -i '/swap/d' /etc/fstab             |                                                                            |
| swapoff -a                              |                                                                            |
| sysctl --system                         |                                                                            |
| scp                                     |                                                                            |
| watch [Command]                         |                                                                            |
| uname -r                                |                                                                            |
| ip a s | less                           |                                                                            |
| echo -n 'somevalue' | base64            |                                                                            |
| lsb_release -dirc                       |                                                                            |
| alias [nameAlias]="commandAlisa"        |                                                                            |
| pulseaudio -k                           |                                                                            |
|                                         |                                                                            |





## General.

| Key/Command                             | Description                                                                |
| --------------------------------------- | -------------------------------------------------------------------------- |
| sudo [command]                          | Run command with the security privileges of the superuser (Super User DO). |
| pwd                                     | Full path to working directory.                                            |
| cat                                     | Concatenate to screen.                                                     |
| clear                                   | Clears the screen.                                                         |
| top                                     | Displays active processes. Press q to quit.                                |
| htop                                    | Displays active processes. Press q to quit.                                |
| open [file]                             | Opens a file (as if you double clicked it).                                |
| reset                                   | Resets the terminal display.                                               |
| alias                                   | Show all alias.                                                            |
| history                                 | Show history.                                                              |
| whoami                                  | Show currently user used.                                                  |
| which [nameApp]                         | Linux which command is used to identify the location of a given executable that is executed when you type the executable name (command) in the terminal prompt. |                                                          |
| lsblk                                   |                                                                            |
| df -h                                   |                                                                            |
| free -h                                 | Show RAM memory. Human-readable.                                           |
| free -m                                 | Show RAM memory.                                                           |
| nproc                                   | Number of CPU.                                                             |
| uptime                                  | Show time of operating system.                                             |
| dpkg -L [namePackage]                   | Shows you what files the package installed.                                |
|                                         |                                                                            |

`echo "export PATH=$PATH:/pathToExecutableFile" >> /etc/bash.bashrc`
`echo -n 'someValue' | base64`
`echo -n 'encodedValue' | base64 --decode`




## Ports.

| Key/Command                             | Description                                                                |
| --------------------------------------- | -------------------------------------------------------------------------- |
| sudo lsof -i -P -n | grep LISTEN        |                                                                            |
| sudo lsof -i -P -n                      |                                                                            |
| sudo lsof -i:[numberPort]               |                                                                            |
| sudo fuser -k [portNumber]/tcp          |                                                                            |
| sudo fuser [portNumber]/tcp             |                                                                            |
| netstat -tulpn | grep LISTEN            |                                                                            |
| netstat -nltp | grep [nameApp]          |                                                                            |
|                                         |                                                                            |





## Process Management.

| Key/Command                             | Description                                                                |
| --------------------------------------- | -------------------------------------------------------------------------- |
| ps -a                                   | Show list of processes.                                                    |
| ps -ef                                  | Show list of processes.                                                    |
| ps aux                                  | Show list of processes.                                                    |
| killall [nameProcess]                   | Kill process by name.                                                      |
| pkill -f 'java -jar'                    |                                                                            |
| jps                                     | Java Virtual Machine Process Status Tool.                                  |
| jps -l                                  |                                                                            |
| jps -v                                  |                                                                            |
| ps -ef | grep [nameProcess]             |                                                                            |
|                                         |                                                                            |

`ps -a | grep [nameProcess]` Show process by name.





## Navigation.

| Key/Command              | Description                                      |
| ------------------------ | ------------------------------------------------ |
| cd [folder]              | Change directory e.g. `cd Documents`.            |
| cd [path]                | Change directory e.g. `cd /home/user/Documents`. |
| cd                       | Home directory.                                  |
| cd ~                     | Home directory.                                  |
| cd /                     | Root of drive.                                   |
| cd ..                    | Previous directory.                              |
| cd ../../                | Move 2 levels up.                                |
| ls                       | Short listing.                                   |
| ls -l                    | Long listing.                                    |
| ls -a                    | Listing incl. hidden files.                      |
| ls -la                   | Long listing incl. hidden files.                 |
| ls -lh                   | Long listing with Human readable file sizes.     |
| ls -lah                  |                                                  |
| ls -R                    | Entire content of folder recursively.            |
| ll                       |                                                  |
| la                       |                                                  |
| colorls                  |                                                  |
| colorls -a               |                                                  |
| colorls -la              |                                                  |
|                          |                                                  |




## File Management.

| Key/Command              | Description                                          |
| ------------------------ | ---------------------------------------------------- |
| touch [file]             | Create a new file.                                   |
| rm [file]                | Remove a file, e.g. `rm data.tmp`.                   |
| rm -i [file]             | Remove with confirmation.                            |
| rm -f [file]             | Force removal without confirmation.                  |
| cp [file] [newFileName]  | Copy file to file.                                   |
| cp [file] [dir]          | Copy file to directory.                              | 
| mv [file] [newFileName]  | Move/Rename, e.g. `mv file1.ad /tmp`.                |
| less [file]              | Output file content delivered in screensize chunks.  |
| find . -name <filename>  | Finding Nested Files.                                |
|                          |                                                      |



## Directory Management.

| Key/Command          | Description                                             |
| -------------------- | ------------------------------------------------------- |
| mkdir [dir]          | Create new directory.                                   |
| mkdir -p [dir]/[dir] | Create nested directories.                              |
| rmdir [dir]          | Remove directory (only operates on empty directories).  |
| rm -R [dir]          | Remove directory and contents.                          |
| rm -r [dir]          | Remove a directory and contents.                        |
| rm -rf [dir]         | Force removal a directory and contents.                 |
| du -sch ./*          | Current Directory Size                                  |
| du -ah -d 1          |                                                         |
| du -h -d 1           |                                                         |
|                      |                                                         |





## curl

| Key/Command                             | Description                                                                                                            |
| --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| -#, --progress-bar                      | Make curl display a simple progress bar instead of the more informational standard meter.                              |
| -b, --cookie <name=data>                | Supply cookie with request. If no =, then specifies the cookie file to use (see -c).                                   |
| -c, --cookie-jar <file name>            | File to save response cookies to.                                                                                      |
| -d, --data <data>                       | Send specified data in POST request. Details provided below.                                                           |
| -f, --fail                              | Fail silently (don't output HTML error form if returned).                                                              |
| -F, --form <name=content>               | Submit form data.                                                                                                      |
| -H, --header <header>                   | Headers to supply with request.                                                                                        |
| -i, --include                           | Include HTTP headers in the output.                                                                                    |
| -I, --head                              | Fetch headers only.                                                                                                    |
| -k, --insecure                          | Allow insecure connections to succeed.                                                                                 |
| -L, --location                          | Follow redirects.                                                                                                      |
| -o, --output <file>                     | Write output to . Can use --create-dirs in conjunction with this to create any directories specified in the -o path.   |
| -O, --remote-name                       | Write output to file named like the remote file (only writes to current directory).                                    |
| -s, --silent                            | Silent (quiet) mode. Use with -S to force it to show errors.                                                           |
| -v, --verbose                           | Provide more information (useful for debugging).                                                                       |
| -w, --write-out <format>                | Make curl display information on stdout after a completed transfer. See man page for more details on available variables. Convenient way to force curl to append a newline to output: -w "\n" (can add to ~/.curlrc).|
| -X, --request                           | The request method to use.                                                                                             |
|                                         |                                                                                                                        |

* `curl -H "Content-Type: application/json" -X GET http://localhost:8080`
* `curl -H "Content-Type: application/json" -X POST http://localhost:8080`
* `curl -H "Content-Type: application/json" -X PATCH http://localhost:8080`
* `curl -H "Content-Type: application/json" -X DELETE http://localhost:8080`
* `curl -d '{"key1":"value1", "key2":"value2"}' -H "Content-Type: application/json" -X POST http://localhost:8080`




## Permission.

| Key/Command                       | Description                             |
| --------------------------------- | --------------------------------------- |
| chmod +x [file]                   | Give permission to execute the file.    |
|                                   |                                         |




## Iptables Management.

| Key/Command                                                   | Description                                                                                     |
| ------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| sudo iptables-save                                            | View the current configuration for IPv4.                                                        |
| sudo ip6tables-save                                           | View the current configuration for IPv6.                                                        |
| sudo vim /etc/network/if-up.d/iptables-rules                  | Create a script with a dump of iptables rules.                                                  |
| sudo chmod +x /etc/network/if-up.d/iptables-rules             | We make the iptables script executable.                                                         |
| sudo /etc/network/if-up.d/iptables-rules                      | Load the iptables rules.                                                                        |
| sudo iptables -L                                              | Show list of rules.                                                                             |
|                                                               |                                                                                                 |




## Ip6tables Management.

| Key/Command                                                   | Description                                                                                     |
| ------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| sudo ip6tables-save                                           | View the current configuration for IPv6.                                                        |
| sudo vim /etc/network/if-up.d/ip6tables-rules                 | Create a script with a dump of ip6tables rules.                                                 |
| sudo chmod +x /etc/network/if-up.d/ip6tables-rules            | We make the ip6tables script executable.                                                        |
| sudo /etc/network/if-up.d/ip6tables-rules                     | Load the ip6tables rules.                                                                       |
|                                                               |                                                                                                 |





## Search.

| Key/Command                       | Description                                                                                     |
| --------------------------------- | ----------------------------------------------------------------------------------------------- |
| find [dir] -name [search_pattern] | Search for files, e.g. `find /Users -name "file.txt"`.                                          |
| grep [search_pattern] [file]      | Search for all lines that contain the pattern, e.g. `grep "Tom" file.txt`.                      |
| grep -r [search_pattern] [dir]    | Recursively search in all files in specified directory for all lines that contain the pattern.  |
| grep -v [search_pattern] [file]   | Search for all lines that do NOT contain the pattern.                                           |
| grep -i [search_pattern] [file]   | Search for all lines that contain the case-insensitive pattern.                                 |
|                                   |                                                                                                 |




## System and Service Managements.

| Alias                                               | Command                                                                                               |
| --------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| systemctl list-unit-files                           |                                                                                                       |
| systemctl list-units                                |                                                                                                       |
| systemctl --all                                     |                                                                                                       |
| systemctl --failed                                  |                                                                                                       |
| systemctl status [nameService]                      | Show status of service.                                                                               |
| systemctl status [nameService.service]              | Show status of service.                                                                               |
| systemctl start [nameService.service]               | Start the service.                                                                                    |
| systemctl stop [nameService.service]                | Stops the service.                                                                                    |
| systemctl restart [nameService.service]             | Restart the service.                                                                                  |
| systemctl enable [nameService.service]              | Enable to starts on boot.                                                                             |
| systemctl disable [nameService.service]             | Disable to start on boot.                                                                             |
| systemctl is-enabled [nameService]                  | Check status of service enabled or disabled.                                                          |
| service --status-all                                |                                                                                                       |
| systemctl daemon-reload                             |                                                                                                       |
|                                                     |                                                                                                       |

`systemctl list-units | grep .service`
`systemctl list-unit-files | grep .service`





## Log Managements.

| Key/Command                                              | Description                                                                                     |
| -------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| journalctl                                               | Show every journal entry that is in the system will be displayed within a page.                 |
| journalctl -b                                            | Displaying logs from the current Boot.                                                          |
| journalctl --list-boots                                  | To see the boots that journald knows about.                                                     |
| journalctl -u [name]                                     | To see all of the logs from an unit name our system.                                            |
| journalctl -p [priorityLevel]                            | To see all of the logs at a priority level on you system.                                       |
| journalctl -p err                                        |                                                                                                 |
| journalctl -p crit                                       |                                                                                                 |
| journalctl -n                                            | To display a set amount of records.                                                             |                                                                                                |
| journalctl -f                                            | To actively follow the logs as they are being writen.                                           |
|                                                          |                                                                                                 |





## Groups Managements.

| Key/Command                                               | Description                                                                |
| --------------------------------------------------------- | -------------------------------------------------------------------------- |
| gpasswd -a [userName] [groupName]                         | Add user to the group.                                                     |
| getent group [groupName]                                  |                                                                            |
|                                                           |                                                                            |





## Alias.

| Alias                             | Command                                                                                               |
| --------------------------------- | ----------------------------------------------------------------------------------------------------- |
| h                                 | history                                                                                               |
| history                           | omz_history                                                                                           |
|                                   |                                                                                                       |
| l                                 | ls -CF                                                                                                |
| lS                                | ls -1FSsh                                                                                             |
| la                                | ls -A                                                                                                 |
| lart                              | ls -1Fcart                                                                                            |
| ldot                              | ls -ld .*                                                                                             |
| ll                                | ls -alF                                                                                               |
| lr                                | ls -tRFh                                                                                              |
| lrt                               | ls -1Fcrt                                                                                             |
| ls                                | ls --color=auto                                                                                       |
| lsa                               | ls -lah                                                                                               |
| lt                                | ls -ltFh                                                                                              |
| mv                                | mv -i                                                                                                 |

* hsi `history | grep -i`
* hs `history | grep`




## Alias for Kubernetes.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kaf                                                                               | kubectl apply -f                                                                                      |
| kdel                                                                              | kubectl delete                                                                                        |
| kdelf                                                                             | kubectl delete -f                                                                                     |
| keti                                                                              | kubectl exec -ti                                                                                      |
| kga                                                                               | kubectl get all                                                                                       |
| k                                                                                 | kubectl                                                                                               |
| kca                                                                               | _kca(){ kubectl "$@" --all-namespaces;  unset -f _kca; }; _kca                                        |
| kclean                                                                            | sudo aptitude remove -P ?and(~i~nlinux-(ima|hea) ?not(~n`uname -r`))                                  |

| kcp                                                                               | kubectl cp                                                                                            |




## Alias for Kubernetes Node.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kdelno                                                                            | kubectl delete node                                                                                   |
| keno                                                                              | kubectl edit node                                                                                     |
| kgno                                                                              | kubectl get nodes                                                                                     |
| kdno                                                                              | kubectl describe node                                                                                 |





## Alias for Kubernetes Pod.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kdelp                                                                             | kubectl delete pods                                                                                   |
| kep                                                                               | kubectl edit pods                                                                                     |
| kdp                                                                               | kubectl describe pods                                                                                 |
| kgp                                                                               | kubectl get pods                                                                                      |
| kgpa                                                                              | kubectl get pods --all-namespaces                                                                     |
| kgpl                                                                              | kgp -l                                                                                                |
| kgpwide                                                                           | kgp -o wide                                                                                           |
| kgpw                                                                              | kgp --watch                                                                                           |
|                                                                                   |                                                                                                       |





## Alias for Kubernetes ReplicaSet.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kgrs                                                                              | kubectl get rs                                                                                        |





## Alias for Kubernetes Deployment.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kdd                                                                               | kubectl describe deployment                                                                           |
| kdeld                                                                             | kubectl delete deployment                                                                             |
| ked                                                                               | kubectl edit deployment                                                                               |
| kgd                                                                               | kubectl get deployment                                                                                |
| kgda                                                                              | kubectl get deployment --all-namespaces                                                               |
| ksd                                                                               | kubectl scale deployment                                                                              |
| krsd                                                                              | kubectl rollout status deployment                                                                     |
| kgdwide                                                                           | kgd -o wide                                                                                           |
| kgdw                                                                              | kgd --watch                                                                                           |
|                                                                                   |                                                                                                       |





## Alias for Kubernetes Namespace. ns

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kdelns                                                                            | kubectl delete namespace                                                                              | 
| kdns                                                                              | kubectl describe namespace                                                                            |
| kens                                                                              | kubectl edit namespace                                                                                |
| kgaa                                                                              | kubectl get all --all-namespaces                                                                      |
| kgns                                                                              | kubectl get namespaces                                                                                |
|                                                                                   |                                                                                                       |





## Alias for Kubernetes Config.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kccc                                                                              | kubectl config current-context                                                                        |
| kcdc                                                                              | kubectl config delete-context                                                                         |
| kcgc                                                                              | kubectl config get-contexts                                                                           |
| kcn                                                                               | kubectl config set-context $(kubectl config current-context) --namespace                              |
| kcsc                                                                              | kubectl config set-context                                                                            |
| kcuc                                                                              | kubectl config use-context                                                                            |





## Alias for Kubernetes Service. svc

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kgsa                                                                              | kubectl get svc --all-namespaces                                                                      |
| kds                                                                               | kubectl describe svc'                                                                                 |
| kgs                                                                               | kubectl get svc                                                                                       |
| kdels                                                                             | kubectl delete svc                                                                                    |
| kes                                                                               | kubectl edit svc                                                                                      |
| kgswide                                                                           | kgs -o wide                                                                                           |
| kgsw                                                                              | kgs --watch                                                                                           |
| kgsswide                                                                          | kgss -o wide                                                                                          |
| kgssw                                                                             | kgss --watch                                                                                          |
|                                                                                   |                                                                                                       |





## Alias for Kubernetes Configmap. cm

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kdcm                                                                              | kubectl describe configmap                                                                            | 
| kdelcm                                                                            | kubectl delete configmap                                                                              | 
| kecm                                                                              | kubectl edit configmap                                                                                | 
| kgcm                                                                              | kubectl get configmaps                                                                                | 
| kgcma                                                                             | kubectl get configmaps --all-namespaces                                                               | 
|                                                                                   |                                                                                                       |





## Alias for Kubernetes Logs.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kl                                                                                | kubectl logs                                                                                          | 
| kl1h                                                                              | kubectl logs --since 1h                                                                               |
| kl1m                                                                              | kubectl logs --since 1m                                                                               |
| kl1s                                                                              | kubectl logs --since 1s                                                                               |
| klf                                                                               | kubectl logs -f                                                                                       |
| klf1h                                                                             | kubectl logs --since 1h -f                                                                            |
| klf1m                                                                             | kubectl logs --since 1m -f                                                                            |
| klf1s                                                                             | kubectl logs --since 1s -f                                                                            |





## Alias for Kubernetes Secret.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kdelsec                                                                           | kubectl delete secret                                                                                 |
| kgseca                                                                            | kubectl get secret --all-namespaces                                                                   |
| kgsec                                                                             | kubectl get secret                                                                                    |
| kdsec                                                                             | kubectl describe secret                                                                               |





## Alias for Kubernetes PersistentVolumeClaim.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kgpvca                                                                            | kubectl get pvc --all-namespaces                                                                      |
| kgpvc                                                                             | kubectl get pvc                                                                                       |
| kdpvc                                                                             | kubectl describe pvc                                                                                  |
| kepvc                                                                             | kubectl edit pvc                                                                                      |
| kdelpvc                                                                           | kubectl delete pvc                                                                                    |
| kgpvcw                                                                            | kgpvc --watch                                                                                         |
|                                                                                   |                                                                                                       |




## Alias for Kubernetes Ingress.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kgia                                                                              | kubectl get ingress --all-namespaces                                                                  |
| kdeli                                                                             | kubectl delete ingress                                                                                |
| kdi                                                                               | kubectl describe ingress                                                                              |
| kgi                                                                               | kubectl get ingress                                                                                   |
| kei                                                                               | kubectl edit ingress                                                                                  |





## Alias for Kubernetes Statefulset.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kgssa                                                                             | kubectl get statefulset --all-namespaces                                                              |
| kdss                                                                              | kubectl describe statefulset                                                                          |
| kdelss                                                                            | kubectl delete statefulset                                                                            |
| kess                                                                              | kubectl edit statefulset                                                                              |
| ksss                                                                              | kubectl scale statefulset                                                                             |
| krsss                                                                             | kubectl rollout status statefulset                                                                    |
| kgss                                                                              | kubectl get statefulset                                                                               |





## Alias for Kubernetes Port Forwarding.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| kpf                                                                               | kubectl port-forward                                                                                  |





## Alias for Kubernetes Rollout.

| Alias                                                                             | Command                                                                                               |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| krh                                                                               | kubectl rollout history                                                                               |
| kru                                                                               | kubectl rollout undo                                                                                  |





## Articles.





## Conferences.





## Conference Speakers.





## Help.
