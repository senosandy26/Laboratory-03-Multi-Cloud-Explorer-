Laboratory-03-Multi-Cloud-Explorer

# Checkpoint 7 – Continue Your Linux Investigation

## Linux System Information

I launched a Linux environment using the KillerCoda Playground and used Linux commands to identify the system information.

### 1. Operating System

**Command:**

```bash
cat /etc/os-release
```

This command displays information about the Linux distribution and version.

**Result:**

```text
[Paste your OS information here]
```

### 2. CPU Information

**Command:**

```bash
lscpu
```

This command displays information about the CPU, including the architecture, CPU model, number of CPUs, and cores.

**Result:**

```text
[Paste your CPU information here]
```

### 3. Memory

**Command:**

```bash
free -h
```

This command displays the total, used, and available memory in a human-readable format.

**Result:**

```text
[Paste your memory information here]
```

### 4. Disk Space

**Command:**

```bash
df -h
```

This command displays the disk space used and available on the Linux filesystem.

**Result:**

```text
[Paste your disk space information here]
```

## Cloud Migration Options

If this Linux server were migrated to the cloud, it could be hosted using virtual machine services from AWS, Microsoft Azure, or Google Cloud Platform.

| Cloud Provider      | Service                | Purpose                                                                      |
| ------------------- | ---------------------- | ---------------------------------------------------------------------------- |
| **AWS**             | Amazon EC2             | Hosts Linux servers as virtual machines in the cloud.                           |
| **Microsoft Azure** | Azure Virtual Machines | Offers scalable Linux virtual machines that allow for server workloads.           |
| **Google Cloud**    | Compute Engine         |  Provides customizable virtual machines (VMs) that can host Linux operating systems. | 

### Conclusion

The Linux server can be ported to any of the three major cloud platforms. All three cloud services, **Amazon EC2**, **Azure Virtual Machines**, and **Google Compute Engine**, are equivalent services because they enable organizations to deploy Linux-based virtual machines in the cloud. This will vary based on the needs of the company, including cost, performance, existing company infrastructure, security needs, and cloud services offered.
