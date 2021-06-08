# scel2rime

A library to onvert Sogou scel file to rime dictionary file.

## Usage

    from scel2rime import scel2rime

    # scel_file_path: str
    # output_rime_dict_path: str
    # dict_name: str, should correspond to output_file_dict_path
    #   i.e. output_rime_dict_path = '~/.config/ibus/rime/sogou.custom.yaml'
    #        dict_name             = 'sogou'
    # version: str, usually date. i.e. '2021-06-08'
    scel2rime(scel_file_path, output_rime_dict_path, dict_name, version)
