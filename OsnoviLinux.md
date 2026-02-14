чо такое ос
чо такое ядро ос

ктрл + альт + ф3 - ос
ктрл + альт + ф1 - обратно к интерфейсу
htop
pipe |
man (manual)
prstree
mc - главная менюшка
--help - подскажи к bash(!)

отличие set и export?

type не
which
chmod
export PATH=$PATH:`pwd`
ctrl+R

---

осшки:(prekol`nye)
qnx, astra linux

не будем смотреть: .acl, .lsatr не нада пока

будем: ls -a, chmod
ls -a: 
type(-(файлик), l(ссылка), d(directory), b(блочный), c(поточный)), 
w(write), r(read), x(execute) - я,
rwx - группа,
rwx - все
for example: -rw-r--r--

readelf
chmod a+x test-file

задумайтесь(!): о шифрованной файловое системе

mount
dd if=/dev/zero of=secret-data bs=300M count=1 //count обязатлеьно!!!! иначе будет до конца места //лучше в эмуляторе
hexdump
mkfs.ext4 //antipod - wipefs
sudo mount -o loop

диск это файлик, можно из файлика  сделать устройство -> записать туда другие файлы

