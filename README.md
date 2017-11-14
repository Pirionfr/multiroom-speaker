# multiroom speaker ansible

Set of playbook roles to orchestrate Sonos like speaker with an orangepi, should also work with rpi, powered by Ansible.

## Getting Started

Run the playbook

```
ansible-playbook -i inventory/ site.yml --ask-pass --ask-become-pass
```


### Prerequisites

In order to use the roles you should first ensure that you have Ansible installed.

To clone the entire project and use the included playbooks:

```
git clone https://github.com/Pirionfr/multiroom-speaker.git
```



## Built With

* [mopidy](https://www.mopidy.com/) - player
* [upmpdcli](https://www.lesbonscomptes.com/upmpdcli/) - dlna renderer
* [airplay-sync](https://github.com/mikebrady/shairport-sync) - AirPlay audio player


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

