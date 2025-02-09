
#per lancio su google colab
!pip install pygit2==1.15.1
%cd /content
!git clone https://github.com/lllyasviel/Fooocus.git (stava qui prima ma io l'ho scaricato in locale)
%cd /content/Fooocus
!python entry_with_update.py --share --always-high-vram
