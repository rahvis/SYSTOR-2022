# SYSTOR '22: 15th ACM International Conference on Systems and Storage 

The work was done in collaboration with **Dell Technologies**. <br>
Paper: https://dl.acm.org/doi/abs/10.1145/3534056.3534997 <br>

# Abstract 
Disk scrubbing is a background process to fix read errors by reading the disks. However, scrubbing the entire storage array can significantly increase the system load and degrade system performance when there is high incoming IO. Deciding "which disk to scrub" complemented with "when to scrub" can significantly improve the data centre's overall reliability and power saving. We present a solution on an open-source SMART dataset that performs selective scrubbing and designs a scrub frequency based on the scrub cycle. The method leverages an algorithmic randomness framework to quantify the health of the concerned drives and ranks them for selective scrubbing.
<br>

<img width="1197" alt="Screenshot 2023-09-21 at 2 13 38 PM" src="https://github.com/rahvis/SYSTOR-2022/assets/64368687/def74274-2b72-486e-8860-39de4735f803">

# Citation
```
@inproceedings{vishwakarma2022selective,
  title={Selective scrubbing based on algorithmic randomness},
  author={Vishwakarma, Rahul and Liu, Bing and Gatsby, Peter and Hwang, Jinha},
  booktitle={Proceedings of the 15th ACM International Conference on Systems and Storage},
  pages={141--141},
  year={2022}
}
```
```
@misc{liu2022managing,
  title={Managing storage device scrubbing},
  author={Liu, Bing and Vishwakarma, Rahul Deo},
  year={2022},
  month=jan # "~20",
  publisher={Google Patents},
  note={US Patent App. 16/928,155}
}
```
