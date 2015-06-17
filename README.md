# DevStack

Cài đặt Openstack sử dụng Devstack

###Chuẩn bị:

- Một máy cài OS ubuntu, tối thiểu 4gb RAM, 1 NIC mạng

###Cài đặt

**Chú ý** Dùng tài khoản khác root (VD: uvdc)

```sh
sudo apt-get install git wget -y
git clone -b stable/icehouse https://github.com/openstack-dev/devstack.git
cd devstack/
wget -O localrc http://goo.gl/OeOGqL
./stack.sh
```

##Done

## Update với bản Kilo

```sh
sudo apt-get install git wget -y
git clone -b stable/kilo https://github.com/openstack-dev/devstack.git
cd devstack/
./stack.sh
```

=> Nhập mật khẩu cho các thành phần trong quá trình cài đặt
