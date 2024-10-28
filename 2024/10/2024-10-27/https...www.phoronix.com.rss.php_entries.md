# Source:Phoronix, URL:https://www.phoronix.com/rss.php, language:en-us

## Linux Working On A Counter To Keep Track Of The Number Of Hung Tasks Since Boot
 - [https://www.phoronix.com/news/Linux-hung_task_detect_count](https://www.phoronix.com/news/Linux-hung_task_detect_count)
 - RSS feed: $source
 - date published: 2024-10-27T09:24:00+00:00

Sent out in original patch form this past week and already iterated to a second version this Sunday, a new proposal is underway to introduce "hung_task_detect_count" as a convenient means of tracking the number of times hung tasks are detected since boot...

## Linux 6.12-rc5 Disabling Intel's Linear Address Masking "LAM" Due To Security Concerns
 - [https://www.phoronix.com/news/Linux-Disabling-Intel-LAM](https://www.phoronix.com/news/Linux-Disabling-Intel-LAM)
 - RSS feed: $source
 - date published: 2024-10-27T07:30:00+00:00

Intel merged Linear Address Masking into the Linux kernel last year as a means of allowing user-space to store metadata within some bits of pointers without masking it out before use. LAM can be useful for virtual machines, sanitizers / profiling / memory tagging, and other uses. While the brand new Intel Arrow Lake and Lunar Lake CPUs support LAM, the Linux kernel is now disabling LAM out of security concerns...

## Intel's PCIe Cooling Driver Ready For Linux 6.13 To Reduce Bandwidth When Running Hot
 - [https://www.phoronix.com/news/Linux-6.13-PCIe-Cooling-Driver](https://www.phoronix.com/news/Linux-6.13-PCIe-Cooling-Driver)
 - RSS feed: $source
 - date published: 2024-10-27T07:01:26+00:00

For the past year Intel software engineers have been developing a PCIe cooling driver to reduce the PCIe link speed to cope with thermal issues. In the future with PCI Express 6.0 this driver may be further adapted to also reduce the PCIe link width when encountering thermal problems. This cooling driver is now ready for merging with the upcoming Linux 6.13 kernel...

## Linux NETFS Patches Help With CIFS Performance, Single Blob Objects
 - [https://www.phoronix.com/news/Linux-NETFS-Better-Reads](https://www.phoronix.com/news/Linux-NETFS-Better-Reads)
 - RSS feed: $source
 - date published: 2024-10-27T06:27:55+00:00

The Linux NETFS code as a network file-system helper library is seeing patches to help enhance the read performance for solutions like CIFS as well as adding single blob object support...

## DM-INLINECRYPT Being Worked On To Leverage Inline Block Device Encryption
 - [https://www.phoronix.com/news/DM-INLINECRYPT-Patches](https://www.phoronix.com/news/DM-INLINECRYPT-Patches)
 - RSS feed: $source
 - date published: 2024-10-27T06:15:59+00:00

In addition to Eric Biggers of Google being busy working on various crypto and hashing performance optimizations, the longtime Linux developer has also been working on "dm-inlinecrypt" for better leveraging inline block device encryption...

