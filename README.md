# preshrink-vm-virtualbox_linux_guest_shrink_preparation_tool

1. Description:

 Preshrink-VM is a tool that prepares Linux VirtualBox VM's to be shrunk with
 the vboxmanage modifyhd </path/to/thedisk.vdi> --compact command. All free
 space must be set to "zeros" for the command to work most efficiently.

2. Installation:

 Unzip the "preshrink-vm" bash script from the zip archive and move it to either
 /usr/local/bin or ~/bin. You can either do this from a command line or simply
 drag the file out of Archive Manager to wherever you'd like it to go.

 Note: scripts that are run from the ~/bin directory cannot be prefixed with
 'sudo' as the system will fail to find them. Those who intend to run
 PreShrink-VM from a script for cron, anacron or systemd timers should place it
 in /usr/local/bin This is also the best practice if there are more than one
 administrator accounts on the machine.

3. License.

 PreShrink-VM is free softare. You can redistribute it and/or modify it under
 the terms of the GNU General Public License Version 2.0. as published by
 the Free Software Foundation. A copy of the GNU GPL 2.0 is provided with the
 software.

4. Contents of Help Page:

 Preshrink-VM is a tool that prepares Linux VirtualBox VM's to be shrunk with
 the vboxmanage modifyhd </path/to/thedisk.vdi> --compact command. All free
 space must be set to "zeros" for the command to work most efficiently.

 It's a good idea to delete unawnted files, empty the trash and clear caches
 before shrinking your VM.

 Commands:

    preshrink-vm = prepares VM with one active partition:

    preshrink-vm --home = prepares VM with a separate /home partition.

    preshrink-vm --help = shows this help page.

 By Joe Collins www.ezeelinux.com (GNU/General Public License version 2.0)

 Disclaimer:

 THIS SOFTWARE IS PROVIDED BY EZEELINUX “AS IS” AND ANY EXPRESS OR IMPLIED
 WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
 MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
 EVENT SHALL EZEELINUX BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
 EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
 PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR
 BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER
 IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
 ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
 POSSIBILITY OF SUCH DAMAGE.

