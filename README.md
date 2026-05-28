# CCNA Preparation labs from Jeremy IT Labs YouTube course

This is the repo where I store and share all the labs I did from [this course](https://www.youtube.com/playlist?list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ) as preparation for the CCNA exam. Some days' labs may be missing, it is because I either skipped the topic as I already knew it very well or I did a similar or the same lab already.

Also you can get the incomplete lab files to try it out yourself over [here](https://drive.google.com/drive/folders/1PwK_jWqfUtOjV7gHt8ODutq9QA5cxCgi?usp=sharing).

## Repo Structure

All the days are folders in the root of this repo. And in each day, there is a packet tracer binary lab file (completed), and the `.conf` files are copy pasted content of `show running-config` command on each network device with the same name as the file name in that day's lab. Sometimes there may be 2 labs in the same day in which case there will be sub folders inside that particular day's folders.

Here is a sample clip of the repo structure:
```
├── Day-08
│   ├── Day 08 Lab - IPv4 Addresses.pkt
│   └── R1.conf
├── Day-11
│   ├── part-1-configuring
│   │   ├── Day 11 Lab - Configuring Static Routes.pkt
│   │   ├── R1.conf
│   │   ├── R2.conf
│   │   └── R3.conf
│   └── part-2-troubleshooting
│       ├── Day 11 Lab - Troubleshooting Static Routes.pkt
│       ├── R1.conf
│       ├── R2.conf
│       └── R3.conf
├── Day-16
│   ├── Day 16 Lab - VLANs (Part 1).pkt
│   ├── R1.conf
│   └── SW1.conf
├── Day-17
│   ├── Day 17 Lab - VLANs (Part 2).pkt
│   ├── R1.conf
│   ├── SW1.conf
│   └── SW2.conf
```

Each day's folder may also include a `README.md` with notes on what the lab covers, with an `assets` subfolder containing screenshots.
