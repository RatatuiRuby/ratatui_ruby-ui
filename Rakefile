# frozen_string_literal: true

#--
# SPDX-FileCopyrightText: 2026 Kerrick Long <me@kerricklong.com>
# SPDX-License-Identifier: AGPL-3.0-or-later
#++

require "bundler/gem_tasks"
require "ratatui_ruby/devtools"

RatatuiRuby::Devtools.install!

# Import project-specific tasks
Dir.glob("tasks/*.rake").each { |r| import r }

task default: %w[lint:fix test lint reuse]
