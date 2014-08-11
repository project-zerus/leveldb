cc_library(
  name = 'leveldb',
  warning = 'no',
  export_incs = [
    './include',
  ],
  incs = [
    '.',
    './include',
  ],
  defs = [
    'LEVELDB_PLATFORM_POSIX',
    'SNAPPY',
  ],
  srcs = [
    'db/builder.cc',
    'db/c.cc',
    'db/dbformat.cc',
    'db/db_impl.cc',
    'db/db_iter.cc',
    'db/filename.cc',
    'db/log_reader.cc',
    'db/log_writer.cc',
    'db/memtable.cc',
    'db/repair.cc',
    'db/table_cache.cc',
    'db/version_edit.cc',
    'db/version_set.cc',
    'db/write_batch.cc',
    'helpers/memenv/memenv.cc',
    'port/port_posix.cc',
    'table/block_builder.cc',
    'table/block.cc',
    'table/filter_block.cc',
    'table/format.cc',
    'table/iterator.cc',
    'table/merger.cc',
    'table/table_builder.cc',
    'table/table.cc',
    'table/two_level_iterator.cc',
    'util/arena.cc',
    'util/bloom.cc',
    'util/cache.cc',
    'util/coding.cc',
    'util/comparator.cc',
    'util/crc32c.cc',
    'util/env.cc',
    'util/env_posix.cc',
    'util/filter_policy.cc',
    'util/hash.cc',
    'util/histogram.cc',
    'util/logging.cc',
    'util/options.cc',
    'util/status.cc',
    'util/testharness.cc',
    'util/testutil.cc'
  ],
  deps = [
    '#pthread',
    '//snappy:snappy'
  ]
)
