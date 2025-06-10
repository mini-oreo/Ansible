# Ansible

echo "alias anr='ansible-navigator run -m stdout'" >> ~/.bashrc
echo "alias ansc='ansible-navigator run -m stdout --syntax-check'" >> ~/.bashrc
echo "alias d='ansible-navigator doc -m stdout'" >> ~/.bashrc

echo "autcmd FileType yaml setlocal ts=2 sw=2 sts=2 ai et cuc nu" >> ~/.vimrc