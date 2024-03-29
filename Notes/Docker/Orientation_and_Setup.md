
# Get Started, Part 1: Orientation and setup

---

* Docker is to develop, deploy and run applications with containers

* Containerization is the use of Linux containers to deploy applications and is increasingly popular because containers are:
  * Flexible: Even the most complex applications can be containerized.
  * Lightweight: Containers leverage and share the host kernel.
  * Interchangeable: You can deploy updates and upgrades on-the-fly.
  * Portable: You can build locally, deploy to the cloud, and run anywhere.
  * Scalable: You can increase and automatically distribute container replicas.
  * Stackable: You can stack services vertically and on-the-fly.

---

* A container is launched by running an image

* An image is an executable package that includes everything needed to run an application--the code, a runtime, libraries, environment variables, and configuration files.

* A container is a runtime instance of an image--what the image becomes in memory when executed (that is, an image with state, or a user process).
  * A container runs natively on Linux and shares the kernel of the host machine with other containers. It runs a discrete process, taking no more memory than any other executable, making it lightweight.
  * By contrast, a virtual machine (VM) runs a full-blown “guest” operating system with virtual access to host resources through a hypervisor. In general, VMs provide an environment with more resources than most applications need. 

---