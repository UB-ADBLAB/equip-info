Server and workstation information
====================================

## Mailing list

Please post annoucements and updates to
[cse-adblab@buffalo.edu](mailto:cse-adblab@buffalo.edu).

If you need to run time-sensitive experiments on the servers, please (1) update
and commit `booking.md`; and (2) email the date/time period, server(s) needed,
to the mailing list above. Please try to make the annoucement ahead of time
(e.g., a few hours) so people will have time to save their works. If your jobs
require changing system configurations, clearing I/O buffers, or rebooting the
servers, please let people know at least one day ahead of time.

As soon as you finish the jobs, please remove your entry from `booking.md` and
commit. (Optional) feel free to send another email to let everyone know that
the server is now free to use.

## List of servers and workstations

| hostname | model | service tag |  location | root user | port | config |
| ------------- | ------- | -------- | -------- | ------- | ----- | ------ |
| arches | Dell PowerEdge R650 | BKB42G3 | Davis 339E | zzhao35 | 22/5522 | - Ubuntu 22.04 LTS <br>- 6330(2GHz,28C/56T) x2<br>- DDR4-3200 32GBx16<br>- P5800X 400GB, `/mnt/ssd1`<br>- Samsung 870EVO 2TB x3 `/mnt/ssd{2-4}`|
| TBA | Dell PowerEdge R660 | | Davis 339E | zzhao35 |  | - Ubuntu ?? <br>- 8562Y+(2.8GHz,32C/64T)<br>- DDR5-5600 32GBx16<br>- TBD|
| db01 | Dell Precision 3650 | 63LC0M3 | Davis 338I | zzhao35 | 3389 | |
| db02 | Dell Precision 3650 |  | Davis 338Y | yunnanyu | 3389 | |
| db03 | Dell Precision 3660 |  | Davis 338Y | cwang39 | 3389 | |
| dds03 | Dell Precision 3660 | | Davis 338Y | zimmerm3 | 22 | |

FQDN is `<hostname>.cse.buffalo.edu`.

