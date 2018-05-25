# ALVR - Air Light VR

ALVR��PCVR�̉�ʂ�Gear VR��Oculus Go�ɓ]�����ėV�Ԃ��߂̃\�t�g�ł��BSteamVR�̃Q�[�����X�^���h�A�����^�̃w�b�h�Z�b�g�Ńv���C���邱�Ƃ��ł��܂��B

[English](https://github.com/polygraphene/ALVR/) Japanese

## ����
ALVR��PCVR�̉�ʂ��G���R�[�h��Wi-Fi�o�R�Ńw�b�h�Z�b�g�ɓ]�����܂��B�����\�t�g�Ƃ���Riftcat��Trinus VR������܂����A��������Gear VR�����ɓ������Ă���̂������ł��BWi-Fi�o�R�ł�Gear VR�ɓ��ڂ��ꂽAsynchronous Timewarp�𗘗p���ăX���[�Y�ȃw�b�h�g���b�L���O�������ł��܂��B

## �����
�ȉ��̓�������K�v�ł��B
- Gear VR �� Oculus Go
 - ����AGear VR + Galaxy S8�ł��������Ă��܂���BS6��S7���ƃX�y�b�N�I�Ɍ�������������܂���B
 - ����������������t�B�[�h�o�b�N���肢���܂��I
- NVENC���g����NVIDIA GPU�𓋍ڂ����n�C�G���hPC
 - ���݁AWindows 10�̂݃T�|�[�g���Ă��܂��B
- 802.11n/ac Wi-Fi
- SteamVR���C���X�g�[���ς݂ł��邱��

## �C���X�g�[�����@
- ALVR server�̃C���X�g�[��������@
 - [Releases](https://github.com/polygraphene/ALVR/releases)����zip���_�E�����[�h
 - �C�ӂ̃t�H���_�ɓW�J
 - driver�t�H���_����driver\_install.bat�����s
 - ALVR.exe���N��
- ALVR client���w�b�h�Z�b�g�ɃC���X�g�[��������@
 - Gear VR
  - SideloadVR�o�R�ł̃C���X�g�[�����y�ł�
 - Oculus Go
  - [Releases](https://github.com/polygraphene/ALVR/releases)����apk���_�E�����[�h
  - adb��apk���C���X�g�[��

## �A���C���X�g�[�����@
- driver�t�H���_����driver\_uninstall.bat�����s
- �C���X�g�[���t�H���_���폜 (���W�X�g���͎g���܂���)
- driver\_uninstall.bat�����s�����폜���Ă��܂����ꍇ
    - C:\Users\%USERNAME%\AppData\Local\openvr\openvrpaths.vrpath���������ŊJ���C���X�g�[���t�H���_���m�F(�蓮�ŏ����������Ȃ��悤��)
    - �R�}���h�v�����v�g��
    `"C:\Program Files (x86)\Steam\steamapps\common\SteamVR\bin\win32\vrpathreg.exe" removedriver (�C���X�g�[���t�H���_)`
    �����s

## ����̗\��
- ����r�b�g���[�g�̕ύX�@�\
- �����̃X�g���[�~���O�̃T�|�[�g
- H.265�̃T�|�[�g (����AH.264�̂�)
- Gear VR / Oculus Go �R���g���[���̃T�|�[�g
- �C���X�g�[���̍쐬

## �r���h���@
### ALVR Server and GUI(Launcher)
- ALVR.sln��Visual Studio 2017�ŊJ���ăr���h���܂��B
 - alvr\_server: C++�ŏ����ꂽSteamVR (OpenVR) �̃h���C�o
 - ALVR: C#�ŏ����ꂽGUI��ALVR Server���N�����邽�߂̃v���O����

### ALVR Client
- [ALVR Client](https://github.com/polygraphene/ALVRClient)���N���[��
- [osig file](https://developer.oculus.com/documentation/mobilesdk/latest/concepts/mobile-submission-sig-file/) �� assets �t�H���_�ɐݒu (Gear VR�̂�)
- Android Studio�Ńr���h
- adb�ŃC���X�g�[��

## License
MIT���C�Z���X�ł��B
ALVR is licensed under MIT License.

## Donate
If you like this project, please donate!
