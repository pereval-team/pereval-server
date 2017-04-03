ENV['VAGRANT_DEFAULT_PROVIDER'] = 'docker'
ENV['VAGRANT_CHECKPOINT_DISABLE'] = 'false'

VAGRANTFILE_API_VERSION = '2'

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.synced_folder ".", "/vagrant", disabled: true

  config.vm.define 'openwebspider' do |conf|
    conf.vm.provider 'docker' do |docker|
      docker.image = 'pantyusha/openwebspider'
      docker.name = 'openwebspider'
    end
    conf.vm.network "forwarded_port", guest: 9999, host: 81
  end

  config.vm.define 'cyberchef' do |conf|
    conf.vm.provider 'docker' do |docker|
      docker.image = 'mpepping/cyberchef'
      docker.name = 'cyberchef'
    end
    conf.vm.network "forwarded_port", guest: 8000, host: 82
  end
end